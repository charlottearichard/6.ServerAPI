# 6.ServerAPIs

## Description 


## Things Learned 
- 'Endpoints': specifies which resource you can access, it is building off of URLs 

- 'curl': which stands for client URL (cURL) command line tool used to transfer data to and from a server. 

- 'Promise': object is like a result of what should occur from a fuction

- Asynchronous: a promised base behavior that will run everything that is outside of the fetch before so the 'client/user' will have something to look at while data is being fetched or gathered. Will allow many things to happen at once ("alert()" is not asynchronous)
    - example: 
    
   > var getUserRepos = function(){
   > fetch("https://api.github.com/users/octocat/repos")
   > .then(function(response){
   > console.log("inside", response);
   >  });
   > console.log("outside");
   > };

- JSON: JavaScript Object Notation

- Create responsive collumns with col 

- .addEventListener: method that attach a specific event to an element. When a button is clicked it "fetches" desired data. 