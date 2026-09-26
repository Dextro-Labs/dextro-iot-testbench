// Build no Jenkins (dextro-pipeline). O GitHub Actions saiu: todo build roda
// no Jenkins desde 26/09/2026.
@Library('dextro-pipeline') _

dextroLib(stack: 'cmake', build: 'git clone --depth 1 https://github.com/marcosdxt/dextro-iot-cpp-lib.git ../dextro-iot-cpp && (cd ../dextro-iot-cpp && git clone --depth 1 https://github.com/LiamBindle/MQTT-C.git external/mqtt-c && cmake -B build && cmake --build build) && npm install && IOT_BINARY_PATH=$PWD/../dextro-iot-cpp/build/examples/iot-example node index.js')
