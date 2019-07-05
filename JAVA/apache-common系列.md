# [apache-common系列](http://commons.apache.org/)
[apache-common官网](http://commons.apache.org/)

[转自网址](https://my.oschina.net/u/2450666/blog/2054604)
<table border="1" cellpadding="1" cellspacing="1"> 
 <tbody> 
  <tr> 
   <td style="width:90px">功能</td> 
   <td style="width:90px">描述</td> 
   <td style="width:150px">类</td> 
   <td>说明</td> 
  </tr> 
  <tr> 
   <td>Commons-Lang3</td> 
   <td>封装了一些常用的工具类； 在研发阶段优先使用该包中提供的工具类；</td> 
   <td>AnnotationUtils<br> ArchUtils<br> ArrayUtils<br> BitField<br> BooleanUtils<br> CharSequenceUtils<br> CharSetUtils<br> CharUtils<br> ClassPathUtils<br> ClassUtils<br> EnumUtils<br> LocaleUtils<br> ObjectUtils<br> RandomStringUtils<br> RandomUtils<br> SerializationUtils<br> StringUtils<br> SystemUtils<br> ThreadUtils<br> RegExUtils<br> Validate</td> 
   <td>提供对注解的一系列操作；<br> 提供快速获取CPU基本信息的操作；<br> 提供对数组的一系列操作；<br> 提供对Bit的一系列操作；<br> 提供对boolean或Boolean的一系列操作；<br> 提供对一组字符串的一系列操作，会将String转成CharSequence；<br> 提供对一组字符串的一系列操作，会将String专程CharSet；<br> 提供对char或Char的一系列操作；<br> 提供对ClassPath的一系列操作；<br> 提供对Java类的一系列操作，没有使用反射实现；<br> 提供对Enum的一系列操作；<br> 提供对java.util.Locale的一系列操作；<br> 提供对Object类的一系列操作；<br> 提供一个生成随机字符串的类；<br> 提供一个生成随机数的类；<br> 提供一个序列号的类；<br> 提供对String的一系列操作；<br> 提供一个快速获取操作系统或JVM信息的类；<br> 提供一个快速操作线程或线程组的类；<br> 提供一个正则表达式的操作类；<br> 提供一个简单的验证类，类似断言的用法；</td> 
  </tr> 
  <tr> 
   <td>Commons-Collections4</td> 
   <td>封装了一些操作各种集合 类型的工具类；</td> 
   <td>BagUtils<br> ClosureUtils<br> CollectionUtils<br> ComparatorUtils<br> EnumerationUtils<br> FactoryUtils<br> IterableUtils<br> IteratorUtils<br> ListUtils<br> MapUtils<br> MultiMapUtils<br> MultiSetUtils<br> PredicateUtils<br> QueueUtils<br> SetUtils<br> SplitMapUtils<br> TransformerUtils<br> TrieUtils</td> 
   <td>提供一个操作Bag集合的工具类；<br> 提供一个操作Closure的工具类；<br> 提供一个操作Collection的工具类；<br> 提供一个操作Comparator的工具类；<br> 提供一个操作Enumeration的工具类；<br> 提供一个操作Factory的工具类；<br> 提供一个操作Iterable的工具类；<br> 提供一个操作Iteraotr的工具类；<br> 提供一个操作List的工具类；<br> 提供一个操作Map的工具类；<br> 提供一个操作MultiMap的工具类；<br> 提供一个操作MultiSet的工具类；<br> 提供一个操作Predicate的工具类；<br> 提供一个操作Queue的工具类；<br> 提供一个操作Set的工具类；<br> 提供一个操作SplitMap的工具类；<br> 提供一个操作Transformer的工具类；<br> 提供一个操作Trie的工具类；</td> 
  </tr> 
  <tr> 
   <td>Commons-BeanUtils</td> 
   <td>封装了操作Bean的 工具类；</td> 
   <td>BeanUtils<br> ConstructorUtils<br> ConvertUtils<br> MethodUtils<br> PropertyUtils</td> 
   <td>提供一个操作Bean的工具类；<br> 提供一个操作Bean的构造函数的工具类；<br> 提供一个转换相关的工具类；<br> 提供一个操作Bean方法的工具类；<br> 提供一个操作Bean属性的工具类；</td> 
  </tr> 
  <tr> 
   <td>Commons-CLI</td> 
   <td>封装了读取命令行 的工具类；</td> 
   <td>Options<br> CommandLineParser<br> CommandLine</td> 
   <td>命令行参数定义对象；<br> 命令行参数解析对象；<br> 命令行参数解析对象；</td> 
  </tr> 
  <tr> 
   <td>Commons-IO</td> 
   <td>封装了IO相关的 工具类；</td> 
   <td>IOUtils<br> FileUtils<br> FilenameUtils</td> 
   <td>提供一个操作IO的工具类；<br> 提供一个操作File的工具类；<br> 提供一个根据Filename来获取文件信息的工具类；</td> 
  </tr> 
  <tr> 
   <td>Commons-Math3</td> 
   <td>封装了数学算法 相关的工具类；</td> 
   <td>FunctionUtils<br> ComplexUtils<br> MatrixUtils<br> MapUtils<br> StatUtils<br> TransformUtils<br> ArithmeticUtils<br> CombinatoricsUtils<br> MathUtils</td> 
   <td>提供一个数学函数对象的工具类；<br> 提供一个级数计算的工具类；<br> 提供一个矩阵计算的工具类；<br> 提供一个网格地图的工具类；<br> 提供一个静态统计的工具类；<br> 提供一个转换的工具类；<br> 提供一个算法的工具类；<br> 提供一个组合算法的工具类；<br> 提供一个其他算法的工具类；</td> 
  </tr> 
  <tr> 
   <td>Commons-Compress</td> 
   <td>封装了各种压缩 解压的工具类；</td> 
   <td>BrotliUtils<br> BZip2Utils<br> GzipUtils</td> 
   <td>提供一个处理Brotli压缩格式的工具类；<br> 提供一个处理Zip压缩格式的工具类；<br> 提供一个处理Gzip压缩格式的工具类；</td> 
  </tr> 
  <tr> 
   <td>Commons-Text</td> 
   <td>封装了处理文 本的工具类；</td> 
   <td>CaseUtils<br> StringEscapeUtils<br> WordUtils</td> 
   <td>提供一个单词转换工具类（驼峰转换等）；<br> 提供一个字符串与Html、JS、Json、XML等的转换工具类；<br> 提供一个处理单词的工具类；</td> 
  </tr> 
 </tbody> 
</table> 