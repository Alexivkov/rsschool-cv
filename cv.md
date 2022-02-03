*My name is*  **Alexander Sivkov**, 36 y.o.
| tel      | +79090010078   |
| :---        |    :----:   |
| e-mail:       | sivkov@inbox.ru         | 
| Github     | https://github.com/Alexivkov        | 

I am looking for a **Web developer job**. 
I think that you can constantly improve yourself and everything around you. Ready to learn new things
***
#### Skills:
- **HTML,CSS**
- **JavaScript, Python**
- **Git**
- **Figma**
 ***
 Here is [My JS Calculator](https://alexivkov.github.io/calculator) - [repo for it](https://github.com/Alexivkov/calculator)
***
### Education:
- 2006, Graduated from Ural Federal University, Specialist degree, **electronic systems engineer**
- 2018, **Web developer course** from ITMO University, Saint-Petersburg
- 2019, **Python programming course** from Saint-Petersburg State Technical University
***
**B2** - English language level (*Upper-Intermediate*)
I have 3 months of English practice in the USA (Work and Travel program)
***
### Work Experience
- 2006 - 2007 *Anti theft system Engeneer*
- 2007 - 2015 *Service center organizer*
- 2015 - 2021 *Mobile electronic serviceman*
### My Codewars example:
```
function sqInRect(lng, wdth){
  if(lng==wdth) return null;
  var res = [];
  var sq = lng*wdth;
  while(lng>1){
    if(lng<wdth) {
      res.push(lng); 
      wdth -= lng;
      sq -= lng*lng;
    }else{
      res.push(wdth);
      lng -= wdth;
      sq -= wdth*wdth;
    }
  }
    while(sq>0){
      res.push(1);
      sq--;
    }
    return res;
}```