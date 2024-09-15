* Performing load balancing in spring cloud and integrating spring cloud eureka service registry to invoke external service, need to use feign client instead of rest client.
* Feign client is a declarative http web client developed by Netflix.
* If you want to use Feign, then create an interface and annotate with @FeignClient