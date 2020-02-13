# lemoonBench
lemoonBench工具（别名LBench、柠檬Bench），是一款针对Linux服务器设计的服务器性能测试工具。通过综合测试，可以快速评估服务器的综合性能，为使用者提供服务器硬件配置信息。

LemonBench目前涵盖了如下测试：

服务器基础信息 (CPU信息/内存信息/Swap信息/磁盘空间信息等)

Speedtest网速测试 (本地到最近源及国内各地域不同线路的网速)

磁盘测试 (4K块/1M块 直接写入测试)

路由追踪测试 (追踪到国内和海外不同线路的路由信息)

Spoofer测试 (获取详细网络信息，快速判断服务器接入线路)


fast-mode:
curl -fsL https://raw.githubusercontent.com/whittmy/lemoonBench/master/LemonBenchIntl.sh | bash -s fast

full-mode:
curl -fsL https://raw.githubusercontent.com/whittmy/lemoonBench/master/LemonBenchIntl.sh | bash -s full
