# **Login**

<Code language="javascript">
    fetch("https: //storeapi.demo-api.com/login",{
        method:"POST",
        body:JSON.stringify(
            {
                'username': 'user1',
                'password': 'user1@123
            }
        )
    })
    .then(res=>res.json())
    .then(json=>console.log(json))
</Code>
