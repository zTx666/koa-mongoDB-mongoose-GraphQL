# koa-mongoDB-mongoose-GraphQL
koa+mongoDB+mongoose（增删改查API）+GraphQL（API查询服务）
##mongoDB
	键值对型数据库（JSON）
##mongoose
	编写mongoDB API的中间件
	为数据提供类型验证，在编写mongoDB语句时，数据的正确性提供保障。
	对数据进行类（schema）型化，在其下可添加操作该类的方法,并可以操作该类内部数据的方法
	提供find、select、update、remove等方法进行增删改查
	注意：
	自定义方法用箭头函数会造成this指向错误
	所有回调方法都要使用错误优先原则	
##GraphQL
	对API数据进行验证和筛查，查询以及处理API数据，为API提供UI界面（GraphQL查询服务）
	koa 引入 graphq-server-koa 中间件

后端使用koa+mongoDB+mongoose（增删改查API）+GraphQL（API查询服务）
前端可以通过/graphql访问API查询界面
