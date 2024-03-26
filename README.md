# Pet-store
Project Name: Pet store
Base URL: https://petstore.swagger.io/v2
Collection:[Pet]
            Request 1:POST add pet  /pet
                      Row data : Required,
            Request 2:PUT update pet /pet,
            Request 3:GET find pet by Status  /pet/findByStatus,
            Request 4:GET find pet by id     /pet/{petId},
            Request 5:PATCH update pet from data /pet/{petId}, 
            Request 6:DELETE Delete a pet  /pet/{petId}
Collection:[store]
            Request 1:POST place an order for pet  /store/order
                      Row data : Required,
            Request 2:GET find order by id  /store/order/{orderId},
            Request 3:GET return pet inventory by status  /store/inventory,
            Request 4:DELETE Delete order by id /store/order/{orderId}
Collection:[user]
            Request 1:POST add user /user
                      Row data : Required,
            Request 2:POST create With Array   /user/createWithArray 
                      Row data : Required,
            Request 3:GET get user by name /user/{username},
            Request 4:GET user login   /user/login?{username}&{password},
            Request 5:PUT updated user /user/{username}
                      Row data : Required,
            Request 6:GET user logout /user/logout,
            Request 6:DELETE Delete user  /user/{username} 
