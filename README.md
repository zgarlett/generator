```
 ********** ********  ********
/////**/// /**/////  **////// 
    /**    /**      /**       
    /**    /******* /*********
    /**    /**////  ////////**
    /**    /**             /**
    /**    /**       ******** 
    //     //       ////////  
```

**Getting started** 

```bash
npm install -g yo
git clone https://github.com/gliviu/generator-typescript-template
cd generator-typescript-template
npm install
npm run build

# Link the package to global scope so that yeoman discovers the new generator
npm link

yo --generators # check the generator is in place

yo typescript-template argument1 --option2 secondOption

# Check that ./dummyfile.txt was created according to above CLI arguments

npm run watch    # build generator as development goes
```
