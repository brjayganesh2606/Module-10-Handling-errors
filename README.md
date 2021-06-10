Module-10-Handling-errors

1)Walkthrough10-1: Explore default error handling

http://localhost:8081/flights?code=FOO

![image](https://user-images.githubusercontent.com/70746268/121345219-35a59280-c942-11eb-868e-147609296290.png)

![image](https://user-images.githubusercontent.com/70746268/121345334-5b329c00-c942-11eb-897b-7f61332904a0.png)

http://localhost:8081/flights?airline=delta&code=PDX

![image](https://user-images.githubusercontent.com/70746268/121345765-e3b13c80-c942-11eb-8e53-7636d6c96ac0.png)

![image](https://user-images.githubusercontent.com/70746268/121345877-07748280-c943-11eb-83ae-5fccebde8bc9.png)

http://localhost:8081/flights?airline=american&code=PDX

![image](https://user-images.githubusercontent.com/70746268/121346859-3d663680-c944-11eb-8587-8172842cb40e.png)

![image](https://user-images.githubusercontent.com/70746268/121346923-4bb45280-c944-11eb-9bae-79c32ad65def.png)

http://localhost:8081/flights?airline=american&code=PDX

![image](https://user-images.githubusercontent.com/70746268/121348719-4f48d900-c946-11eb-82d7-13e78a55fb49.png)

http://localhost:8081/flights?airline=american&code=PDX

output application/json --- error.errorType

![image](https://user-images.githubusercontent.com/70746268/121351339-4a395900-c949-11eb-8e37-52841278ef51.png)

output text/plain --- error.description

![image](https://user-images.githubusercontent.com/70746268/121352537-99cc5480-c94a-11eb-95aa-2cf3b6711db8.png)

2)Walkthrough10-2: Handle errors at the application level

![image](https://user-images.githubusercontent.com/70746268/121362477-ba4cdc80-c953-11eb-9717-a26f5c02db6a.png)

![image](https://user-images.githubusercontent.com/70746268/121362606-d6e91480-c953-11eb-8641-e01852faf1cf.png)

![image](https://user-images.githubusercontent.com/70746268/121362700-ebc5a800-c953-11eb-843e-639e91e8e557.png)

![image](https://user-images.githubusercontent.com/70746268/121363961-00567000-c955-11eb-8d1a-389d0c1c6d6b.png)

![image](https://user-images.githubusercontent.com/70746268/121364010-08161480-c955-11eb-8a20-9d9a536d4da7.png)

![image](https://user-images.githubusercontent.com/70746268/121364093-18c68a80-c955-11eb-8e84-2f429b70e450.png)

http://localhost:8081/flights?airline=american&code=PDX

![image](https://user-images.githubusercontent.com/70746268/121364542-807cd580-c955-11eb-968f-02941593bb5f.png)

http://localhost:8081/flights?airline=delta&code=PDX

![image](https://user-images.githubusercontent.com/70746268/121364723-aa35fc80-c955-11eb-97e5-9269bf975ebb.png)

3)Walkthrough10-3: Handle specific types of errors

![image](https://user-images.githubusercontent.com/70746268/121376291-04878b00-c95f-11eb-9a9d-535a6f3bff84.png)

![image](https://user-images.githubusercontent.com/70746268/121376331-0f422000-c95f-11eb-85df-76fa208a1188.png)

4)Walkthrough10-4: Handle errorsat the flow level

![image](https://user-images.githubusercontent.com/70746268/121492043-25e68680-c9f4-11eb-84f6-3cd61d736a84.png)

![image](https://user-images.githubusercontent.com/70746268/121492065-2c74fe00-c9f4-11eb-805b-39a9f431653d.png)

![image](https://user-images.githubusercontent.com/70746268/121492310-65ad6e00-c9f4-11eb-90fd-3e08ab1299e6.png)

![image](https://user-images.githubusercontent.com/70746268/121492358-71009980-c9f4-11eb-86fd-02e67d46664b.png)

![image](https://user-images.githubusercontent.com/70746268/121495278-1fa5d980-c9f7-11eb-8a34-95d3ea0b4956.png)

5)Walkthrough 10-5: Handle errors at the processor level

![image](https://user-images.githubusercontent.com/70746268/121496699-56c8ba80-c9f8-11eb-9a89-9eeacc837446.png)

![image](https://user-images.githubusercontent.com/70746268/121496751-61834f80-c9f8-11eb-80ad-e66724a429ab.png)

![image](https://user-images.githubusercontent.com/70746268/121496824-7364f280-c9f8-11eb-9ffb-6f08a733e1d0.png)

6)Walkthrough 10-6: Map an error to acustom error type

![image](https://user-images.githubusercontent.com/70746268/121498077-b2e00e80-c9f9-11eb-9f3b-cf659a8d118f.png)

![image](https://user-images.githubusercontent.com/70746268/121499449-069f2780-c9fb-11eb-80a4-161edb0a79ae.png)

![image](https://user-images.githubusercontent.com/70746268/121499507-16b70700-c9fb-11eb-9906-a51a477b1d8a.png)

7)Walkthrough 10-7: Review and integrate with APIkit error handlers

![image](https://user-images.githubusercontent.com/70746268/121502073-72828f80-c9fd-11eb-9a25-5271019c3e6a.png)

![image](https://user-images.githubusercontent.com/70746268/121502252-9d6ce380-c9fd-11eb-8436-833491c02902.png)

![image](https://user-images.githubusercontent.com/70746268/121502296-a78ee200-c9fd-11eb-832a-66db901a4b69.png)

![image](https://user-images.githubusercontent.com/70746268/121504939-03f30100-ca00-11eb-9016-1bd217cf29bd.png)

![image](https://user-images.githubusercontent.com/70746268/121505080-2127cf80-ca00-11eb-8429-f2fa2cfcf802.png)

8)Walkthrough 10-8: Set a reconnection strategy for a connector

![image](https://user-images.githubusercontent.com/70746268/121506224-28031200-ca01-11eb-87a4-c3300559ae6f.png)







