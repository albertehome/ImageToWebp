���û�����.png .jpg�ļ�ʱ�����ݿͻ��������webp��ʽ��֧�̶ֳȣ��Զ�ѹ��ΪwebpͼƬ����Ӧ���û���
��֧��webp���û������Դ�ͳͼƬѹ����ʽѹ��ͼƬ����Ӧ���û�

``` 
        public void Configure(IApplicationBuilder app, IHostingEnvironment env)
        {
            ImageToWebp.Factory.Enable(app, env);

            app.Run(async (context) =>
            {
                await context.Response.WriteAsync("Hello World!");
            });

            
        }
```