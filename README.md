# Long-Term Care Assistant

> 2019 Final Year Project at Dongguan University of Technology

## Briefing
A resident management system built with [Vue.js](https://vuejs.org), [Flutter](https://flutter.dev) and [Spring Frameworks](https://spring.io) including user information, health management, geo-fence, announcement, etc. to assist in daily work at long-term care center.  

## Table of Content
- [Briefing](#briefing)
- [Architectures](#architectures)
  - [Web](#web)
  - [Backend](#backend)
  - [Mobile](#mobile)
- [Repositories](#repositories)


## Architectures

[![](https://mermaid.ink/img/eyJjb2RlIjoiZ3JhcGggTFJcbiAgICBBW0Jyb3dzZXIvaU9TL0FuZHJvaWRdIC0tPnxTZW5kIFJlcXVlc3R8IEJbV2ViIFNlcnZlcl1cbiAgICBCIC0tPiB8UXVlcnl8IENbRGF0YWJhc2VdXG4gICAgQyAtLT58UmV0dXJuIERhdGF8IEJcbiAgICBCIC0tPnxSZXNwb25zZXwgQSIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2UsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjpmYWxzZX0)](https://mermaid-js.github.io/mermaid-live-editor/edit##eyJjb2RlIjoiZ3JhcGggTFJcbiAgICBBW0Jyb3dzZXIvaU9TL0FuZHJvaWRdIC0tPnxTZW5kIFJlcXVlc3R8IEJbV2ViIFNlcnZlcl1cbiAgICBCIC0tPiB8UXVlcnl8IENbRGF0YWJhc2VdXG4gICAgQyAtLT58UmV0dXJuIERhdGF8IEJcbiAgICBCIC0tPnxSZXNwb25zfCBBIiwibWVybWFpZCI6IntcbiAgXCJ0aGVtZVwiOiBcImRlZmF1bHRcIlxufSIsInVwZGF0ZUVkaXRvciI6ZmFsc2UsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjpmYWxzZX0)

*Tools, Frameworks, Dependencies:*
```yml
web: 
 - Vue.js:
     Vue-core
     Vue-router
     Vuex
 - Bootstrap
mobile:
 - Flutter
backend:
 - Spring Boot
 - MyBatis
 - MySQL
```

### Web


### Backend

#### General Sequence Diagram: 
[![](https://mermaid.ink/img/eyJjb2RlIjoic2VxdWVuY2VEaWFncmFtXG4gICAgVXNlci0-PitDb250cm9sbGVyOiBSZXF1ZXN0XG4gICAgQ29udHJvbGxlci0-PkNvbnRyb2xsZXI6IEF1dGhlbnRpY2F0aW9uIHdpdGggc2Vzc2lvblxuICAgIENvbnRyb2xsZXItLT4-VXNlcjogQXV0aGVudGljYXRpb24gRmFpbGVkXG4gICAgQ29udHJvbGxlci0-PitTZXJ2aWNlOiBBdXRoZW50aWNhdGlvbiB3aXRoIFVzZXIgY3JlZGVudGlhbHNcbiAgICBTZXJ2aWNlLT4-K0RhdGEgQWNjZXNzIE9iamVjdDogQXV0aGVudGljYXRpb24gU2VydmljZVxuICAgIERhdGEgQWNjZXNzIE9iamVjdC0-PitEYXRhYmFzZTogUXVlcnlcbiAgICBEYXRhYmFzZS0tPj5EYXRhIEFjY2VzcyBPYmplY3Q6ICBSZXR1cm4gUXVlcnkgUmVzdWx0XG4gICAgRGF0YSBBY2Nlc3MgT2JqZWN0LS0-PlNlcnZpY2U6IFJldHVybiBEQU9cbiAgICBTZXJ2aWNlLS0-PkNvbnRyb2xsZXI6IFZlcmlmeSBBdXRoZW50aWNhdGlvblxuICAgIENvbnRyb2xsZXItLT4-VXNlcjogQXV0aGVudGljYXRpb24gRmFpbGVkXG4gICAgQ29udHJvbGxlci0-PkNvbnRyb2xsZXI6IEF1dGhlbnRpY2F0aW9uIFBhc3NcbiAgICBDb250cm9sbGVyLT4-U2VydmljZTogQ29udGludWUgUmVxdWVzdFxuICAgIFNlcnZpY2UtPj5EYXRhIEFjY2VzcyBPYmplY3Q6IFJlcXVlc3QgREFPXG4gICAgRGF0YSBBY2Nlc3MgT2JqZWN0LT4-RGF0YWJhc2U6IFF1ZXJ5XG4gICAgRGF0YWJhc2UtLT4-LURhdGEgQWNjZXNzIE9iamVjdDogUmV0dXJuIFF1ZXJ5IFJlc3VsdFxuICAgIERhdGEgQWNjZXNzIE9iamVjdC0tPj4tU2VydmljZTogUmV0dXJuIERBT1xuICAgIFNlcnZpY2UtLT4-LUNvbnRyb2xsZXI6IEFzc2VtYmxlIEpTT05cbiAgICBDb250cm9sbGVyLS0-Pi1Vc2VyOiBSZWNlaXZlIERhdGFcbiAgICAgICAgICAgICIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2UsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjpmYWxzZX0)](https://mermaid-js.github.io/mermaid-live-editor/edit##eyJjb2RlIjoic2VxdWVuY2VEaWFncmFtXG4gICAgVXNlci0-PitDb250cm9sbGVyOiBSZXF1ZXN0XG4gICAgQ29udHJvbGxlci0-PkNvbnRyb2xsZXI6IEF1dGhlbnRpY2F0aW9uIHdpdGggc2Vzc2lvblxuICAgIENvbnRyb2xsZXItLT4-VXNlcjogQXV0aGVudGljYXRpb24gRmFpbGVkXG4gICAgQ29udHJvbGxlci0-PitTZXJ2aWNlOiBBdXRoZW50aWNhdGlvbiB3aXRoIFVzZXIgY3JlZGVudGlhbHNcbiAgICBTZXJ2aWNlLT4-K0RhdGEgQWNjZXNzIE9iamVjdDogQXV0aGVudGljYXRpb24gU2VydmljZVxuICAgIERhdGEgQWNjZXNzIE9iamVjdC0-PitEYXRhYmFzZTogUXVlcnlcbiAgICBEYXRhYmFzZS0tPj5EYXRhIEFjY2VzcyBPYmplY3Q6ICBSZXR1cm4gUXVlcnkgUmVzdWx0XG4gICAgRGF0YSBBY2Nlc3MgT2JqZWN0LS0-PlNlcnZpY2U6IFJldHVybiBEQU9cbiAgICBTZXJ2aWNlLS0-PkNvbnRyb2xsZXI6IFZlcmlmeSBBdXRoZW50aWNhdGlvblxuICAgIENvbnRyb2xsZXItLT4-VXNlcjogQXV0aGVudGljYXRpb24gRmFpbGVkXG4gICAgQ29udHJvbGxlci0-PkNvbnRyb2xsZXI6IEF1dGhlbnRpY2F0aW9uIFBhc3NcbiAgICBDb250cm9sbGVyLT4-U2VydmljZTogQ29udGludWUgUmVxdWVzdFxuICAgIFNlcnZpY2UtPj5EYXRhIEFjY2VzcyBPYmplY3Q6IFJlcXVlc3QgREFPXG4gICAgRGF0YSBBY2Nlc3MgT2JqZWN0LT4-RGF0YWJhc2U6IFF1ZXJ5XG4gICAgRGF0YWJhc2UtLT4-LURhdGEgQWNjZXNzIE9iamVjdDogUmV0dXJuIFF1ZXJ5IFJlc3VsdFxuICAgIERhdGEgQWNjZXNzIE9iamVjdC0tPj4tU2VydmljZTogUmV0dXJuIERBT1xuICAgIFNlcnZpY2UtLT4-LUNvbnRyb2xsZXI6IEFzc2VtYmxlIEpTT05cbiAgICBDb250cm9sbGVyLS0-Pi1Vc2VyOiBSZWNlaXZlIERhdFxuICAgICAgICAgICAgIiwibWVybWFpZCI6IntcbiAgXCJ0aGVtZVwiOiBcImRlZmF1bHRcIlxufSIsInVwZGF0ZUVkaXRvciI6ZmFsc2UsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjpmYWxzZX0)

### Mobile


## Repositories
- [Web ↗️](https://github.com/puiiyuen/ltc-assistant-frontend)
- [Backend ↗️](https://github.com/puiiyuen/ltc-assistant-backend)
- [Mobile ↗️](https://github.com/puiiyuen/ltc-assistant-mobile)