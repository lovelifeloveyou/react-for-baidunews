React���ķ°ٶ������ֻ�����Ŀ

��Ŀ��飺
һ��ʹ��React����ʵ�ֵ������ֻ���Ӧ�ã��ܹ���������ٶ�����API����Դ�ṩ����
�����š�����������������������ſ�Ƭ�������б��ֲ����š��������š���������
�����ۡ����޼��ء������ء��ص������������

1.ǰ��ʹ��react-routerʵ��·�ɣ�ʹ��Axios���ðٶ�����API��ȡ���ݣ����ʹ��
Webpack+Babel+Expressʵ�ֶ�����̬��Դ��������
2.�ѵ�Ϊ���ðٶ�����API��Ҫ���򣬶��䲢δ�ṩCORS��JSONP��������������ѡ��
�Ͳ��ԣ���������ͨ��http-proxy�м��ʵ�ַ����������
3.ͨ����Ŀ����React�﷨ģʽ��state��props�����ú��÷����������ô�ֵ��Router
��ת����������������WebpackӦ�õȷ����нϴ���ߡ�


��Ҫ����ջ��
  ��ܣ� React 
  ·�ɣ� React-Router 
  ����ˣ� Node.js+Express
  ���� http-proxy 
  ������ߣ� Webpack
  ת�빤�ߣ� Babel
  API���ã� axios

��ҪĿ¼�嵥��
  static�� ��̬��ԴĿ¼
  app�� Ӧ�ô�����Ŀ¼
  app->components�� �������Ŀ¼
  app->fetch�� �첽��������������Ŀ¼
  app->util�� �����������Ŀ¼���
  app->constants�� ��ʼ���������ݴ���Ŀ¼
  app->action��reducers��store: Redux���Ŀ¼

��Ҫ�ļ��嵥��
  .babelrc�� Babel�����ļ�
  .gitignore�� git�����ļ��б�
  package.json�� npm�������ļ�
  server.js�� express�������л���ִ���ļ�
  webpack-dev-config.js�� webpack��������ļ�


npm install

npm start

http://127.0.0.1:3000