# Usage
User user = new User();

#### CREATE USER
```JSONObject newUser = new JSONObject(); ```
```newUser.put("name", "nob1");```
```newUser.put("username", "nob1");```
```newUser.put("email", "nob1.nov@gmail.com");```
```user.create(newUser); ```

#### FIND USER
``` System.out.println(user.find("name", "nob")); ```

#### UPDATE USER
```JSONObject user1 = user.find("name", "sochetra");```
```user1.put("name", "sochetra");```
```user1.put("username", "sochetraNOV");```
```user1.put("email", "sochetra.nov@gmail.com");```
```user.update(user1);```

#### DELETE USER
```user.delete("8");```

# Building Project
```Select on project -> "File" -> "Export" -> "Runnable JAR file" -> select on "Extract required libraries into generated JAR"```

After Build the project create the a new folder called "database" that have to same location with .jar file, and then copy the database from eclipse project to database project.
