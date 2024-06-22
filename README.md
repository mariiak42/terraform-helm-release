# Usage
### Please add the following code 
```
module "app" {
  source    = "mariiak42/release/helm"
  namespace = "default"
  name      = "wordpress"
  wait      = false
  chart     = "./application"
  values = []
}
```