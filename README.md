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
