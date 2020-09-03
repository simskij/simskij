```yaml
# simme.developer.yml

apiVersion: apiextensions.k8s.io/v1beta1
kind: Developer
metadata:
  name: simme
  pronouns:
    - he
    - him
  traits:
    - gopher
    - developer advocate
    - public speaker
    - meetup organizer
spec:
  hobbies:
    - gardening
    - tennis
    - cooking
    - longboarding
    - retro computers
  interests:
    - cloud computing
    - devops
    - chaos engineering
    - performance engineering
    - test automation
    - containers
  communities:
    - name: GDG East Sweden
      url: https://gdg.community.dev/gdg-east-sweden/
    - name: Ministry of Testing Stockholm
      url: https://www.meetup.com/Ministry-of-Testing-Stockholm/
    - name: Containrrr
      url: https://github.com/containrrr
```
