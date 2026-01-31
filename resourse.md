units in css

px - fixed

% - depends on the parent

em - relative to the parent (agar aapne parent ko font-size 20px diya hai to child ke liye 1em ki value hogi 20px)

rem - relative to the root (1rem = 16px)

vw - viewport width (puri screen ki width ke respect me) vh - viewport height (puri screen ki height ke respect me) vmax - viewport maximum vmin - viewport minimum

min-height : kamse kam height hogi, agar extend ho jaye to koi issue nahi hai (kam se kam 85% jyada bhi aa jaye to koi issue nahi)

max height - jyada se jyada kitna hoga (harshita bhiaya 10k kharch karenge, us se upar gya to nahi denge paise)




<!-- 
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html,
body {
    height: 100%;
    width: 100%;
}

.parent {
    height: 100%;
    width: 100%;
    display: grid;
    grid-template-columns: 2fr 1fr 1fr;
    grid-template-rows: 100px 2fr 1fr 1fr;

}

.child {
    height: 100%;
    width: 100%;
    background-color: rgb(5, 87, 60);
    border: 2px solid white;
}

#child1 {
    background-color: crimson;
    grid-column-start: 1;
    grid-column-end: 4;
}

#child5 {
    background-color: lightslategray;
    grid-row-start: 3;
    grid-row-end: 5;
}

#child6 {
    background-color: lightseagreen;
    grid-row-start: 3;
    grid-row-end: 4;
    grid-column-start: 2;
    grid-column-end: 4;
}

#child7 {
    background-color: lightcoral;
    grid-row-start: 4;
    grid-row-end: 5;
    grid-column-start: 2;
}

#child8 {
    background-color: orange;
    grid-row-start: 4;
    grid-row-end: 5;
    grid-column-start: 3;
} -->