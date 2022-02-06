# boot-strap-sand-box #

04/02/2022

This repository will be an excellent source to search through when necessary,

Starting to see classes just like h1, h2 to h6 just adding these classes in a `<h4>` e.g tag it turns to the respective one. 

Note: This repository is based on Bootstrap 4. So, some resources are adapted to work according to the most updated one. 

> HEADINGS

**_class="h"_**

` <!-- HEADINGS -->

    <h1>Heading One<small class="text-muted"> Something</small></h1>
    
    <h2>Heading Two</h2>
    
    <h3 class="h1">Heading Three</h3>
    
    <h4>Heading Four</h4>
    
    <h5>Heading Five</h5>
    
    <h6 class="h2">Heading Six</h6>
 `


> DISPLAY CLASSES


**_class="display_"**

'''

    <h1 class="display-1">Display Heading 1</h1>
    <h1 class="display-2">Display Heading 2</h1>
    <h1 class="display-3">Display Heading 3</h1>
    <h1 class="display-4">Display Heading 4</h1>
    
 '''

> PARAGRAPHS 


**_class="lead_"**

`<p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aperiam dolore repellendus veniam consequatur vero numquam voluptatem quam ab expedita eum, ipsam? Necessitatibus dicta quaerat, vitae dolorum, dolor autem reiciendis sapiente.</p>`

>  STYLE CLASSES 

**_class="font-weight-bold_"**

**_class="font-weight-normal_"**

**_class="font-italic_"**


`

    <p class="font-weight-bold">Bold Text</p>
    <p class="font-weight-normal">Normal Text</p>
    <p class="font-italic"> Italic Text</p>
    
    
 `
 
 
    
 
 > TEXT TRANSFORMS
 
 
_**class="text-lowercase"**_

**_class="text-uppercase"_**

_**class="text-capitalize"**_
    
    `
    
    <p class="text-lowercase">MAKE LOWERCASE</p>
    <p class="text-uppercase">make uppercase</p>
    <p class="text-capitalize">make capitalized</p>
    
    `
    
    
   > BLOCKQUOTES


_
 **class="blockquote"**_
 

`

    <blockquote class="blockquote">
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam blanditiis dignissimos aspernatur quo ipsa fugiat labore odio dolore cupiditate sint unde hic neque impedit, atque sit modi et nobis at.</p>
    </blockquote>

    <blockquote class="blockquote blockquote-reverse">
      <p>This is a blockquote</p>
    </blockquote>
    
    
 `
 

 >  BLOCKQUOTE RIGHT ALIGNED


`

    <blockquote>
    
      <p>This is a blockquote aligned right</p>
      
    </blockquote>
    

`

  >  BLOCKQUOTE WITH FOOTER 

  
`

    <blockquote>
    
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
      
      <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
      
    </blockquote>
    
`


> LISTS 

_**class="list-unstyled"**_

`

    <ul class="list-unstyled">
    
      <li>Lorem ipsum dolor sit amet.</li>
      
      <li>Lorem ipsum dolor sit amet.</li>
      
      <li>Lorem ipsum dolor sit amet.</li>
      
      <li>Lorem ipsum dolor sit amet.</li>
      
    </ul>

    <!-- INLINE LIST -->
    <ul class="list-inline">
      <li class="list-inline-item">Lorem ipsum</li>
      <li class="list-inline-item">Lorem ipsum </li>
      <li >Lorem ipsum </li>
      
    </ul>
    
    
  `
  
  
  > ALIGNMENT

_**class="text-left"**_

_**class="text-center"**_

_**class="text-right"**_

`

    <p class="text-left">Text aligned left</p>
    <p class="text-center">Text aligned center</p>
    <p class="text-right">Text aligned right</pc>
    
`


 > RESPONSIVE ALIGN


_**class="text-sm-right"**_

_**class="text-md-right"**_

_**class="text-lg-right"**_

_**class="text-xl-right"**_

_**class="text-sm-left"**_

_**class="text-md-left"**_


_**class="text-lg-left"**_


_**class="text-xl-left"**_


_**class="text-sm-center"**_

_**class="text-md-center"**_

_**class="text-lg-center"**_

_**class="text-xl-center"**_


`

    <p class="text-sm-right">Right aligned on small or larger</p>
    
    <p class="text-md-right">Right aligned on medium or larger</p>
    
    <p class="text-lg-right">Right aligned on large or larger</p>
    
    <p class="text-xl-right">Right aligned on xl or larger</p>

    <p class="text-sm-left">Left aligned text on small or larger</p>
    
    <p class="text-md-left">Left aligned text on medium or larger</p>
    
    <p class="text-lg-left">Left aligned text on large or wider</p>
    
    <p class="text-xl-left">Left aligned text on extra large or wider</p>

    <p class="text-sm-center">Center aligned text on small or larger</p>
    
    <p class="text-md-center">Center aligned text on medium or larger</p>
    
    <p class="text-lg-center">Center aligned text on large or wider</p>
    
    <p class="text-xl-center">Center aligned text on extra large or wider</p>
    
        
`


 > VERTICAL ALIGNMENT
    
    
   _**class="align-baseline"**_
    
    
   _**class="align-top"**_
    
    
   _**class="align-bottom"**_
    
    
   _**class="align-middle"**_
    
    
   _**class="align-text-top"**_
    
    
   _**class="align-text-bottom"**_
    
    
    
    `    
    
    <span class="align-baseline">baseline</span>
    <span class="align-top">top</span>
    <span class="align-bottom">bottom</span>
    <span class="align-middle">middle</span>
    <span class="align-text-top">text-top</span>
    <span class="align-text-bottom">text-bottom</span>
    

   ` 
   
> TURN BLOCK TO INLINE

_**class="d-inline bg-success**_

_**class="d-inline bg-success"**_

_**class="d-block bg-success"**_


_**class="d-inline-block bg-success"**_


_**class="d-inline-block bg-success"**_


`

    <h1 class="d-inline bg-success">Hello</h1>
    <h1 class="d-inline bg-success">Goodbye</h1>

    <br><br>

    <!-- TURN INLINE TO BLOCK -->
    <span class="d-block bg-success">Block</span>

    <br><br>

    <!-- INLINE BLOCK -->
    <div class="d-inline-block bg-success">
      <h3>Hello</h3>
      This is inline
    </div>
    <div class="d-inline-block bg-success">
      <h3>Hello</h3>
      This is inline
    </div>  
    
    </div>
  
  
  
`

> FLOATS


        <div class="float-left">Float left</div><br>
        <div class="float-right">Float right</div><br>
        <div class="float-none">Float none</div><br>

> RESPONSIVE FLOATS


        <div class="float-sm-right">Float right on small or wider</div><br>
        <div class="float-md-right">Float right on medium or wider</div><br>
        <div class="float-lg-right">Float right on large or wider</div><br>
        <div class="float-xl-right">Float right on extra large or wider</div><br>

        <div class="float-sm-left">Float left on small or wider</div><br>
        <div class="float-md-left">Float left on medium or wider</div><br>
        <div class="float-lg-left">Float left on large or wider</div><br>
        <div class="float-xl-left">Float left on extra large or wider</div><br>

        <div class="float-sm-none">Float none on small or wider</div><br>
        <div class="float-md-none">Float none on medium or wider</div><br>
        <div class="float-lg-none">Float none on large or wider</div><br>
        <div class="float-xl-none">Float none on extra large or wider</div><br>

        <br><br>

> CLEARFIX


        <div class="bg-success clearfix">
            <button class="btn btn-secondary float-left" >Float Left</button>
            <button class="btn btn-secondary float-right">Float Right</button>
        </div>

        <!-- FIXED TOP -->
        <h3 class="fixed-top">Fixed Top</h3>

        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quae iure natus, fuga provident molestias, voluptates molestiae aperiam sit dicta a assumenda nesciunt quos adipisci reprehenderit animi ipsum unde quasi nobis veniam, modi. Fuga natus harum, maxime corporis rerum, maiores delectus aliquam aut quo incidunt dignissimos temporibus? Vitae dolorem accusamus voluptatibus illo aut nam praesentium obcaecati quaerat cupiditate distinctio tempora eius esse fuga, repellat fugit harum quia nihil sit in debitis expedita. Eos, voluptates eum rem voluptatum tempore accusamus soluta enim, animi in voluptatibus aliquam distinctio totam repudiandae necessitatibus quidem consequatur incidunt aliquid ad! Inventore ratione, consequatur eligendi iusto esse iure officia praesentium magni in! Nemo tempora, voluptatem facilis reprehenderit minima reiciendis alias similique est rem debitis id expedita voluptatum porro fugiat magni inventore neque. </p>

>FIXED STICKY


        <h3 class="sticky-top">Sticky</h3>

        <p>Est molestias sunt quae quibusdam sequi odit, iusto expedita tempore aspernatur ipsum, necessitatibus rerum debitis, harum, voluptatibus dolorem. Reprehenderit ex aperiam tempore. Cumque ut iste ullam non pariatur, qui architecto, commodi illo praesentium debitis similique, molestiae harum distinctio inventore incidunt enim atque repudiandae eius molestias exercitationem tempore odio dignissimos iusto officia. Libero quasi dicta quos est eveniet magni deserunt aut vero id ad, incidunt nostrum provident tempora modi placeat voluptatem, quod excepturi ipsam aspernatur necessitatibus molestias possimus veritatis sequi. Minus ducimus maiores debitis, nulla magni eum ratione numquam deleniti sunt et dolorum necessitatibus cumque fugit libero recusandae impedit, quaerat, nemo. Vel temporibus amet alias mollitia aspernatur error sint, doloremque, porro blanditiis quia atque ratione reiciendis, praesentium sed doloribus excepturi. Eius tenetur quis veniam enim atque fugit, a itaque dignissimos iusto, tempore fugiat minima libero quasi exercitationem corrupti nam sequi, doloremque quae repudiandae quisquam iure nisi totam consectetur. Corrupti corporis doloribus dolore iusto perspiciatis ipsum, enim sapiente nobis ullam delectus aperiam eaque harum sequi porro! Reprehenderit hic dolores repellat deleniti, illo nostrum nam at odio quasi quis eaque asperiores culpa doloremque ad velit ullam ratione omnis quae adipisci autem necessitatibus. Quod nam non maiores assumenda quae eius nobis cum suscipit, optio aliquid beatae modi tempora delectus voluptatibus debitis earum natus amet libero itaque quasi expedita, maxime repudiandae! Repudiandae sunt similique eum, provident deserunt vitae. Maxime nostrum, nemo quia eius rerum quas recusandae. Molestiae ullam dignissimos illo eum necessitatibus culpa ea, distinctio maiores molestias aliquam, eligendi soluta cumque odio quaerat cupiditate similique in accusamus dolorum nobis. Ea, rem fugit. Minima quae magni laboriosam possimus corporis quidem recusandae aspernatur dignissimos accusamus adipisci, maiores, tenetur excepturi doloremque eum consequuntur? Expedita possimus sit, vel neque fugiat quo ab? Quaerat alias, molestias rerum repudiandae, iste, voluptatem consequatur ex enim tenetur quidem expedita, provident vel reiciendis. Ea ipsam suscipit ex ab nulla est, aspernatur nesciunt consequatur cumque laudantium. Unde ab earum eius vero obcaecati reiciendis omnis quod culpa harum, modi, possimus molestiae voluptatibus beatae, minima ad accusamus quibusdam! Dolor nostrum impedit culpa nemo expedita, numquam dignissimos totam ex reprehenderit consectetur neque dicta deserunt, recusandae porro ipsa accusamus maxime soluta eum facilis temporibus nesciunt accusantium. Placeat provident facere blanditiis doloremque eos tempora officia doloribus deserunt molestias voluptates velit hic, tenetur cupiditate ab. Hic, unde!</p>

>  FIXED BOTTOM


        <h3 class="fixed-bottom">Fixed Bottom</h3>
     
     
 # Background Colors #
        
 >  TEXT COLORS


    <p class="text-muted">Text Primary Color</p>
    <p class="text-primary">Text Secondary Color</p>
    <p class="text-success">Text Success Color</p>
    <p class="text-info">Text Info Color</p>
    <p class="text-warning">Text Warning Color</p>
    <p class="text-danger">Text Danger Color</p>
    <p class="text-info">Text Light Color</p>
    <p class="text-dark">Text Dark Color</p>
    <p class="text-secondary">Text White Color</p>
        
 >  BACKGROUND COLORS

    <div class="bg-primary text-white">Background Primary Color</div>
    <div class="bg-success text-white">Background Secondary Color</div>
    <div class="bg-info text-white">Background Success Color</div>
    <div class="bg-danger text-white">Background Info Color</div>
    <div class="bg-dark text-white">Background Warning Color</div>
    <div class="bg-light text-dark">Background Danger Color</div>
    
 >  INVISIBLE

    <p>There is something invisible right bellow</p>
    <p class="invisible">Hello</p> 
