BTrace is a safe, dynamic tracing system for the Java platform. BTrace project 
is hosted at http://kenai.com/projects/btrace. See also "docs" directory.


		First,execute 
                    btrace pid
                       connect to my version
		ConsolePrint.println("-------------------------------------------------------------------------------------------------");
		ConsolePrint.println("| CommandName  CommandArgs                       CommandUsage");
		ConsolePrint.println("| time         {clazzname methodname}[interval]  �ռ���Ӧʱ�䲢��ʾ ,��֧����Ƶ���ʱ�䣨s��,;�� ");
		ConsolePrint.println("|                                                time java.lang.Thread start 2");
		ConsolePrint.println("| aggre        {clazzname methodname}[interval]  �ռ���Ӧʱ�䲢�ۼ���ʾ ,��֧����Ƶ���ʱ�䣨s��;�� ");
		ConsolePrint.println("|                                                aggre java.lang.Thread start 2");
		ConsolePrint.println("| call         {clazzname methodname}[interval]  �жϺ����Ƿ񱻵���;�� ");
		ConsolePrint.println("|                                                call java.lang.Thread start 2");
		ConsolePrint.println("| jstack       {clazzname methodname}[interval]  ��ӡָ�������ĵ��ö�ջ;�� ");
		ConsolePrint.println("|                                                jstack java.lang.Thread start 2");
		ConsolePrint.println("| file         {filePath}                        ֧��btraceԭ�з�ʽ������btrace file�ļ�;�� ");
		ConsolePrint.println("|                                                file Test.java");
		ConsolePrint.println("| druid                                          ��ص�ǰdruid����Դ������������� ");
		ConsolePrint.println("|                                                druid");
		ConsolePrint.println("| isearch                                        ��ص�ǰisearch�������Ӧʱ�䣻�� ");
		ConsolePrint.println("|                                                isearch");
		ConsolePrint.println("| sql                                            ��ص�ǰSql�������Ӧʱ�䣬�ۺ���ʾ���� ");
		ConsolePrint.println("|                                                sql");
		ConsolePrint.println("| sqlde                                          ��ص�ǰSql�������Ӧʱ�䣬�ۺ���ʾ,����ʾ��ϸsql���� ");
		ConsolePrint.println("|                                                sql");
		ConsolePrint.println("| quit                                           �˳�btrace���� ");
		ConsolePrint.println("|                                                quit");
		ConsolePrint.println("| ------------------------------------------------------------------------------------------------");	
	