- Add sm-market-0.0.1-SNAPSHOT.jar to shopizer/sm-shop/src/main/webapp/WEB-INF/lib
- Copy tiles-admin-marketing.xml to /WEB-INF/tiles/
- Add tile entry to ShopApplicationConfiguration
- Add MarketingConfiguration.class to ShopApplicationConfiguration: @Import({ CoreApplicationConfiguration.class, MarketingConfiguration.class})
- Add entry <beans:value>classpath:bundles/marketing</beans:value>  to shopizer-servlet-context.xml
- Add entry dependency sm-market to sm-shop pom.xml 