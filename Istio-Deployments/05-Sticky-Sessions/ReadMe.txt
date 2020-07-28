https://dev.to/peterj/what-are-sticky-sessions-and-how-to-configure-them-with-istio-1e1a

curl -H "x-user: ricky" 192.168.210.220:31380/ping (Goes to same POD after 1st request)

curl -H "x-user: rickyXX" 192.168.210.220:31380/ping  (Goes to samae POD)