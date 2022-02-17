# Register mixtures
## What are mixtures?
- Mixtures are defined as complex of multiple chemicals.
    - Examples
        - Solvent mixture
        - Composite material

## Register a new mixture
- Click "ADD MIXTURE" button on the mixture page
![](figs/mixture_add.png)

- You can input basic mixture properties in a similar way to chemicals
![](figs/mixture_basic.png)

## Register new a component chemical
- If you move down the page, you will find "MIXTURE COMPONENTS" section.
- Select chemical components you like
- Following is an exmple of registering a mixture of acetone and LiTFSI
    - Mol ratio of 30/70
    - LiTFSI should be registered as a new chemical in advance
### Register acetone
![](figs/mixture_acetone.png)

### Register LiTFSI
- Click "add another" button to add a new component
- NOTE about bug
    - If you register a new mixture, the nothing may occur even after clicking the button
    - In that case, please SAVE the mixture by clicking "SAVE" or "Save and continue editing"
    - After that, the button will work safely
    - (The bug should be attributed to the nested-inline-form module or django. Fixing it will take some time)

![](figs/mix_add_another.png)

- Select your favorite chemical component and amount
- You can change the order of chemicals in the mixture, by editing "Order" form
![](figs/mix_li.png)

