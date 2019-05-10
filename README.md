# base64_git
图片转base64

依赖包commons-codec-1.11.jar，通过org.apache.commons.codec.binary.Base64转码；

此工具打包后主要提供到jmeter/lib中，通过BeanShell Sampler进行引用，简化入参需要图转base64的接口测试流程
