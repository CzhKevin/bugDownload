# bugDownload
bug下载以及格式转换
1.bug的提取。有deviceId、uifcreateDate、durationBeforeMin、durationAfterMin、fileSize、filePath。6个关键参数。主要功能是从微软网站上获取发生bug的相关事件，通过输入以上参数，输出一个包含json数据的txt文件。
上述六个参数分别对应设备ID、bug的创建时间、bug发生前多少分钟、bug发生后多少分钟、获取文件的限制大小、文件的存储位置。

2.json_to_csv 将得到的txt文件中的json数据转换为csv格式。输入下载的txt文件，得到csv格式的输出。

3.bug_repo_2 数据分析，判断一个bug的发生是否由系统update事件导致。
