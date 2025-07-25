## Design 

The header should be full width and look similar to the below image 

https://github.com/365Evergreen/project-requirements-prompts/blob/Raact/swa-intranet/assets/header.png

## Behaviour 

- The header should be a component that is add to all existing and new pages 
- The header should have a transparent background on page load 
- The header should have a top margin of 0px 
- The background colour should change to white on page scroll 
- A box shadow should also be displayed on scroll 
- The header should have a Z-index of 1000 

## HTML 

<div style="width: 100%; height: 100%; position: relative; background: white; overflow: hidden"> 

    <img style="width: 60px; height: 60px; left: 50px; top: 10px; position: absolute" src="https://placehold.co/60x60" /> 

    <div style="width: 341px; height: 80px; left: 120px; top: 0px; position: absolute; justify-content: center; display: flex; flex-direction: column; color: black; font-size: 36px; font-family: Roboto; font-weight: 400; word-wrap: break-word">365 Evergreen</div> 

    <div style="left: 916px; top: 28px; position: absolute; justify-content: flex-start; align-items: flex-start; gap: 50px; display: inline-flex"> 

        <div style="color: #2B2C34; font-size: 20px; font-family: Plus Jakarta Sans; font-weight: 700; text-transform: capitalize; word-wrap: break-word">Home</div> 

        <div style="color: #2B2C34; font-size: 20px; font-family: Plus Jakarta Sans; font-weight: 700; text-transform: capitalize; word-wrap: break-word">Category</div> 

        <div style="color: #2B2C34; font-size: 20px; font-family: Plus Jakarta Sans; font-weight: 700; text-transform: capitalize; word-wrap: break-word">About Me</div> 

        <div style="justify-content: center; align-items: center; gap: 10px; display: flex"> 

            <div style="width: 17px; height: 17px; position: relative; overflow: hidden"> 

                <div style="width: 13.25px; height: 13.25px; left: 1.42px; top: 1.42px; position: absolute; background: #2B2C34"></div> 

            </div> 

            <div style="color: #2B2C34; font-size: 20px; font-family: Plus Jakarta Sans; font-weight: 700; text-transform: capitalize; word-wrap: break-word">Search</div> 

        </div> 

    </div> 

</div> 

## CSS 

// 365 Evergreen 

color: black; 

font-size: 36px; 

font-family: Roboto; 

font-weight: 400; 

word-wrap: break-word 

--- 

// Home 

color: #2B2C34; 

font-size: 20px; 

font-family: Roboto; 

font-weight: 700; 

word-wrap: break-word 

--- 

// Category 

color: #2B2C34; 

font-size: 20px; 

font-family: Roboto; 

font-weight: 700; 

word-wrap: break-word 

--- 

// About Me 

color: #2B2C34; 

font-size: 20px; 

font-family: Roboto; 

font-weight: 700; 

word-wrap: break-word 

--- 

// Search 

color: #2B2C34; 

font-size: 20px; 

font-family: Roboto; 

font-weight: 700; 

word-wrap: break-word 

 
