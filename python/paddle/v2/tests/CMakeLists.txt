add_test(NAME test_v2_layer
        COMMAND ${PROJ_ROOT}/paddle/.set_python_path.sh -d ${PROJ_ROOT}/python/
        ${PYTHON_EXECUTABLE} ${PROJ_ROOT}/python/paddle/v2/tests/test_layer.py
        WORKING_DIRECTORY ${PROJ_ROOT}/python/paddle)
