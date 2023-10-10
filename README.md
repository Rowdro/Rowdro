<style>
    .hide {
        display: inline-block!important;
    }
    p#discountCountdown {
        font-weight: bold;
        font-size: 14px;
        text-align: right;
        margin-right: -317px;
        margin-left: 20px;
        margin-bottom: 2px } #discountCountdown, span#ComparePrice{
        display: none;
    }
    @media (max-width: 767px) {
        #discountCountdown {
        font-size: 14px;
        margin-right: 0px!important;
        text-align: initial!important;
        margin-right: 0!important;
        margin-left: 0!important;
        margin-top: 13px!important;
        margin-bottom: 0!important;
    }
    .price-container {
        margin-top: -9px !important;
        flex-wrap: wrap !important;
    }
    } 
        .product-single__add-to-cart {
        width: 100%;
        padding: 0px 20px !important;
    }
       [id^="AddToCartForm--template"] {
        background: #e6f6ff !important;
        padding: 10px 0px 5px 0px !important;
        border-radius: 10px 10px 10px 10px !important;
        border: 1px solid #d7d7d7 !important;
      }
      .personalized-form,.styleDSS-parent {
        display: none;
      }
      .product_form_personalized {
        padding:0;
        border-top: 0px solid #0088ff !important;
        background: aliceblue;
        border-top-left-radius: 10px;
        border-top-right-radius: 10px;
    }
      .previewBox {
        background: #e6f6ff;
        padding: 20px 20px 0px 20px;
        border-top: 1px solid #0088ff;
        border-bottom-left-radius: 15px;
        border-bottom-right-radius: 15px
      }
      
      p.line-item-property__field {
        display: none;
      }
      .pl-variant-option.border {
      border: 3px solid #000;
    }
      .previewBox {
        margin-top: 30px;
      }
          .icon-parent, .input_first_name, .input_last_name, .style-parent,.styleDSS-parent    {
        padding-top: 30px;
      }
       
     .styleDSS-parent, .type-parent,.style-parent,  .icon-parent, .input_first_name, .input_last_name ,.prv_text{
         margin:0px 20px;
       }
      
      .input_first_name input, .input_last_name input  {
        width: 100%;
        background: white;
        color: black;
        border: 1px solid #A0A0A0;
        border-radius: 4px;
        padding: 10px 4px;
      }
    .preview {
      display: flex;
      gap: 10px;
      margin-bottom: 10px;
      width: 100%;
    }
    .stamp_preview {
      border: 1px solid #38b6ff;
      display: flex;
      align-items: center;
      justify-content: center;
      justify-content: ce;
      width: 90%;
      padding: 5px;
      gap: 3px;
      height: 60px;
      border-radius: 5px;
      background: white;
    }
    .stamp_preview:hover {
      border: 2px solid #38b6ff;
    }
    .symbol_prev {
      width: 40px;
      height: 40px;
    }
    .stamp_icons {
      flex-direction: column;
    }
    .previewChild {
      width: 60px;
      height: 60px;
      border: 1px solid #38b6ff;
      border-radius: 5px;
    }
    .inputPreview {
      font-size: 16px;
      font-weight: 500;
    }
    .inputPreview2 {
      font-size: 16px;
      /*           transform: translateY(-6px); */
      font-weight: 500;
    }
    .prv_text p {
      font-weight: 600;
      text-align: center;
    }
    .text_wrapper {
      max-height: 45px;
      display: flex;
      flex-direction: column;
    }
    .prev_child {
      margin: 0;
      text-align: center;
    }
    
    /* for implemeting the Icons */
    input[type='radio'] {
      display: none;
    }
    .pl-variant-option {
      width: 66px;
      height: 66px;
      border: 1px solid #A0A0A0;
      border-radius: 5px;
      font-size: 0;
      cursor: pointer;
    }
    .pl-variant-options {
      display: flex;
      flex-wrap: wrap;
      gap: 2px;
    }
    .product-list .pl-variants .pl-variant-option.selected {
      border: 1px solid #A0A0A0 !important;
    }
    
    </style>
    
    
    <div class="product-one">
      
      <div class="type-parent">
            <p>Type: <span class="selected_type"></span></p>
            <div class="pl-variant-options type">
              <div class="pl-variant-option" data-name="Single-sided stamp (black ink only)"></div>
              <div class="pl-variant-option" data-name="Double-sided stamp (black & white ink)"></div>
            </div>
          </div>
      
          <div class="style-parent">
            <p>Style: <span class="selected_style"></span></p>
            <div class="pl-variant-options style">
              <div class="pl-variant-option" data-name="Blue owl"></div>
              <div class="pl-variant-option" data-name="Pink cat"></div>
              <div class="pl-variant-option" data-name="Red lion"></div>
              <div class="pl-variant-option" data-name="Green crocodile"></div>
              <div class="pl-variant-option" data-name="White panda"></div>
              <div class="pl-variant-option" data-name="Yellow dog"></div>
            </div>
          </div>
      
       <div class="styleDSS-parent">
            <p>Style: <span class="selected_styleDSS"></span></p>
            <div class="pl-variant-options styleDSS">
              <div class="pl-variant-option" data-name="Blue owl "></div>
              <div class="pl-variant-option" data-name="Pink cat "></div>
              <div class="pl-variant-option" data-name="Red lion "></div>
              <div class="pl-variant-option" data-name="Green crocodile "></div>
              <div class="pl-variant-option" data-name="White panda "></div>
              <div class="pl-variant-option" data-name="Yellow dog "></div>
            </div>
          </div> 
      
          <div class="icon-parent">
            <p>Icon: <span class="selected_icon"></span></p>
            <div class="pl-variant-options Symbol">
              <div class="pl-variant-option" data-name="Braided heart"></div>
              <div class="pl-variant-option" data-name="Double heart"></div>
              <div class="pl-variant-option" data-name="Cat"></div>
              <div class="pl-variant-option" data-name="Dog"></div>
              <div class="pl-variant-option" data-name="Squirrel"></div>
              <div class="pl-variant-option" data-name="Unicorn"></div>
              <div class="pl-variant-option" data-name="Elephant"></div>
              <div class="pl-variant-option" data-name="Bee"></div>
              <div class="pl-variant-option" data-name="Ladybug"></div>
              <div class="pl-variant-option" data-name="Sun"></div>
              <div class="pl-variant-option" data-name="Pizza"></div>
              <div class="pl-variant-option" data-name="Apple"></div>
              <div class="pl-variant-option" data-name="Watermelon"></div>
              <div class="pl-variant-option" data-name="Pineapple"></div>
              <div class="pl-variant-option" data-name="Plane"></div>
              <div class="pl-variant-option" data-name="Bag"></div>
              <div class="pl-variant-option" data-name="Football"></div>
              <div class="pl-variant-option" data-name="Rugby ball"></div>
              <div class="pl-variant-option" data-name="Butterfly"></div>
              <div class="pl-variant-option" data-name="Car"></div>
              <div class="pl-variant-option" data-name="Lion"></div>
              <div class="pl-variant-option" data-name="Dino"></div>
              <div class="pl-variant-option" data-name="Teddy Bear"></div>
              <div class="pl-variant-option" data-name="No symbol"></div>
            </div>
          </div>
          <div class="input_wrapper">
            <div class="input_first_name">
              <label>Name:</label>
              <input name="first_name" maxlength="15" />
            </div>
            <div class="input_last_name">
              <label>Last Name(Optional):</label>
              <input name="first_name" maxlength="13" />
            </div>
          </div>
    
      <div class="previewBox">
         <div class="prv_text">
       <p>Your Stamp Preview 👇
    
    </p>
    
    </div>
          <div class="preview">
            <div class="stamp_preview">
              <div class="symbol_prev"></div>
              <div class="text_wrapper">
                <div class="inputPreview"></div>
                <div class="inputPreview2"></div>
              </div>
            </div>
            <div class="previewChild"></div>
          </div>
      </div>
      
     <p class="line-item-property__field">
         <!-- <input novalidate id="type-message" name="properties[Type]" type="text"> -->
        <input novalidate id="style-message" name="properties[Style]" type="text">
        <input novalidate id="icon-message" name="properties[Icon]" type="text">
        <input novalidate id="name-message" name="properties[Name]" type="text">
        <input novalidate id="ename-message" name="properties[Last Name]" type="text">
        </p>
      
        </div>
    
    
    <script>
      var icons = {
        'Red lion':
        'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzMjA5MTE5MDA5NTAtTFJDLTE0MjMtbWluLmpwZyIsImVkaXRzIjp7InJlc2l6ZSI6eyJ3aWR0aCI6MjAwLCJmaXQiOiJjb250YWluIn19fQ==',
      'Green crocodile':
        'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzMjA5MTE5MDA5NTAtTFJDLTE0MjAtbWluLmpwZyIsImVkaXRzIjp7InJlc2l6ZSI6eyJ3aWR0aCI6MjAwLCJmaXQiOiJjb250YWluIn19fQ==',
      'Blue owl':
        'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzMjA5MTE5MDA5NTAtMjAyMjAzMzAtX0RTQzQyNDgtbmV3LW1pbi5qcGciLCJlZGl0cyI6eyJyZXNpemUiOnsid2lkdGgiOjIwMCwiZml0IjoiY29udGFpbiJ9fX0=',
      'Pink cat':
        'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzMjA5MTE5MDA5NTAtMjAyMjAzMzAtX0RTQzQyNDUtbmV3LW1pbi5qcGciLCJlZGl0cyI6eyJyZXNpemUiOnsid2lkdGgiOjIwMCwiZml0IjoiY29udGFpbiJ9fX0=',
      'White panda':
        'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzMjA5MTE5MDA5NTAtTFJDLTE0MTgtbWluLmpwZyIsImVkaXRzIjp7InJlc2l6ZSI6eyJ3aWR0aCI6MjAwLCJmaXQiOiJjb250YWluIn19fQ==',
      'Yellow dog':
        'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzMjA5MTE5MDA5NTAtTFJDLTE0MjUtbWluLmpwZyIsImVkaXRzIjp7InJlc2l6ZSI6eyJ3aWR0aCI6MjAwLCJmaXQiOiJjb250YWluIn19fQ==',
        'Single-sided stamp (black ink only)':'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzNzcyMjY5NTI5ODItZG93bmxvYWQtMjAyMy0wNy0xMVQyMzQ4MjguODAwLnBuZyIsImVkaXRzIjp7InJlc2l6ZSI6eyJ3aWR0aCI6MjAwLCJmaXQiOiJjb250YWluIn19fQ==',
        'Double-sided stamp (black & white ink)':'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzNzcyMjY5NTI5ODItZG93bmxvYWQtMjAyMy0wNy0xMVQyMzQ5MDUuNjg1LnBuZyIsImVkaXRzIjp7InJlc2l6ZSI6eyJ3aWR0aCI6MjAwLCJmaXQiOiJjb250YWluIn19fQ==',
        'Red lion ':
        'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzOTI1MDU2MjI4MDYtMy5MaW9uLmpwZyIsImVkaXRzIjp7InJlc2l6ZSI6eyJ3aWR0aCI6MjAwLCJmaXQiOiJjb250YWluIn19fQ==',
      'Green crocodile ':
        'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzOTI1MDU2MjI4MDYtNC5Dcm9jb2RpbGUuanBnIiwiZWRpdHMiOnsicmVzaXplIjp7IndpZHRoIjoyMDAsImZpdCI6ImNvbnRhaW4ifX19',
      'Blue owl ':
        'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzOTI1MDU2MjI4MDYtMS5Pd2wuanBnIiwiZWRpdHMiOnsicmVzaXplIjp7IndpZHRoIjoyMDAsImZpdCI6ImNvbnRhaW4ifX19',
      'Pink cat ':
        'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzOTI1MDU2MjI4MDYtMi5DYXQuanBnIiwiZWRpdHMiOnsicmVzaXplIjp7IndpZHRoIjoyMDAsImZpdCI6ImNvbnRhaW4ifX19',
      'White panda ':
        'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzOTI1MDU2MjI4MDYtNS5QYW5kYS5qcGciLCJlZGl0cyI6eyJyZXNpemUiOnsid2lkdGgiOjIwMCwiZml0IjoiY29udGFpbiJ9fX0=',
      'Yellow dog ':
        'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgzOTI1MDU2MjI4MDYtNi5Eb2cuanBnIiwiZWRpdHMiOnsicmVzaXplIjp7IndpZHRoIjoyMDAsImZpdCI6ImNvbnRhaW4ifX19',
      'Braided heart':
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/1.png?v=1675177378',
      Chrocodile:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/1.png?v=1675177378',
      'Double heart':
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/2_fb2f0b35-ded9-4097-b638-c3524d791321.jpg?v=1675177378',
      Cat:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/3.png?v=1675177378',
      Dog: 'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/4.png?v=1675177378',
      Squirrel:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/5.jpg?v=1675177378',
      Unicorn:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/6.jpg?v=1675177378',
      Elephant:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/7.jpg?v=1675177377',
      Bee:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/8.jpg?v=1675177377',
      Ladybug:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/9.jpg?v=1675177378',
      Sun:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/10.png?v=1675177378',
      Pizza:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/11.jpg?v=1675177377',
      Pineapple:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/14.png?v=1675177378',
      Apple:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/12..png?v=1675177378',
      Watermelon:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/13.png?v=1675177378',
      Plane:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/15.png?v=1675177378',
      Bag:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/16.png?v=1675177378',
      Football:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/17.png?v=1675177378',
      'Rugby ball':
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/18.png?v=1675177378',
      Butterfly:
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/19.png?v=1675177378',
      Car: 'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/20.png?v=1675177378',
      Lion: 'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/21.png?v=1675177378',
      Dino: 'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/22_2.png?v=1675177378',
      'Teddy Bear':
        'https://cdn.shopify.com/s/files/1/0567/6679/1817/files/23.png?v=1675177378',
      'No symbol':
        'https://d17fzo7x83uajt.cloudfront.net/eyJidWNrZXQiOiJiY3BvIiwia2V5Ijoia2lkZG9zcGFjZS11cy5teXNob3BpZnkuY29tLzgyNTI5Nzg5MjE3NTAtRVlKSURXMS5KUEUiLCJlZGl0cyI6eyJyZXNpemUiOnsid2lkdGgiOjIwMCwiZml0IjoiY29udGFpbiJ9fX0=',
    };
    
    // =============== Main Function
    //============== to get the values and setting up the previews
    // previews have their own function and we are calling them back inside the getVal function
    
    function getVal(p) {
      // Selecting the elements
      let product = document.querySelector(`.${p}`);
      let allVars = product.querySelectorAll('.pl-variant-option');
    
      let selectedType = product.querySelector('.selected_type');
       let selectedStyle = product.querySelector('.selected_style');
      let selectedStyleDSS = product.querySelector('.selected_styleDSS');
      let selectedIcon = product.querySelector('.selected_icon');
    
      let styleVariantOptions = product.querySelectorAll(
        '.style .pl-variant-option'
      );
       let typeVariantOptions = product.querySelectorAll(
        '.type .pl-variant-option'
      );
      let styleDSSVariantOptions = product.querySelectorAll(
        '.styleDSS .pl-variant-option'
      );
      let symbolVariantOptions = product.querySelectorAll(
        '.Symbol .pl-variant-option'
      );
      let inputFirstNameP = product.querySelector('.input_first_name');
      let inputFirstName = inputFirstNameP.querySelector('input');
    
      let inputLastNameP = product.querySelector('.input_last_name');
      let inputLastName = inputLastNameP.querySelector('input');
    
      // let capturerParent = product.querySelector('.capturer');
      let capturer = product.querySelector('#custom-message');
      let styleCapturer = product.querySelector('#style-message');
      let iconCapturer = product.querySelector('#icon-message');
      let nameCapturer = product.querySelector('#name-message');
      let enameCapturer = product.querySelector('#ename-message');
    //   let typeCapturer = product.querySelector('#type-message');
      
    // console.log(submitBtn)
    
      // For setting the previews
    
      let symbolPreview = product.querySelector('.symbol_prev');
      let textWrapper = product.querySelector('.text_wrapper');
      let stylePreview = product.querySelector('.previewChild');
    
      let textWrapperFirstName = textWrapper.querySelector('.inputPreview');
      let textWrapperLastName = textWrapper.querySelector('.inputPreview2');
    
      let selectedTypeVariantOption;
      let selectedStyleVariantOption;
       let selectedStyleDSSVariantOption;
      let selectedSymbolVariantOption;
    
      // stickers
    
      // let stickerNameP = product.querySelector('.sticker_name');
      // let stickerNameC = stickerNameP.querySelector('input');
    
      stylePreview.setAttribute(
        'style',
        `background: url('${icons['Blue owl']}') center top / cover;`
      );
    
      // Setting the images here for vars
    
      allVars.forEach((e) => {
        let grabValue = e.getAttribute('data-name');
        e.setAttribute(
          'style',
          `background: url('${icons[`${grabValue}`]}') center top / cover;`
        );
      });
    
      // getting the type value here
      typeVariantOptions.forEach((option) => {
        option.addEventListener('click', function () {
          selectedTypeVariantOption = this.getAttribute('data-name');
          selectedType.textContent = this.getAttribute('data-name');
        });
      });
       // getting the style value here
      styleVariantOptions.forEach((option) => {
        option.addEventListener('click', function () {
          selectedStyleVariantOption = this.getAttribute('data-name');
          selectedStyle.textContent = this.getAttribute('data-name');
        });
      });
      // getting the style value here
      styleDSSVariantOptions.forEach((option) => {
        option.addEventListener('click', function () {
          selectedStyleDSSVariantOption = this.getAttribute('data-name');
          selectedStyleVariantOption = this.getAttribute('data-name');
          selectedStyleDSS.textContent = this.getAttribute('data-name');
    
          console.log(selectedStyleDSS, selectedStyleDSSVariantOption)
        });
      });
    
      // getting the icon value here
    
      symbolVariantOptions.forEach((option) => {
        option.addEventListener('click', function () {
          selectedSymbolVariantOption = this.getAttribute('data-name');
          selectedIcon.textContent = this.getAttribute('data-name');
        });
      });
    
      // pushing all the values to an input
    
     
      // It will check if atc button exist
    // This interval checks if the "Add to Cart" button exists
    const myInterval = setInterval(() => {
    
        // Check if the "Add to Cart" button element exists in the DOM
    
        if (document.querySelector('button.btn.btn--primary.btn--add-to-cart.full[type="submit"]')) {
    
            // Store the initial HTML content of the "Add to Cart" button
            const mainAtcButton = document.querySelector(".product-single__add-to-cart").innerHTML;
    
            // Get a reference to the first name input field and add an input event listener
            let fName = document.querySelector('[name="first_name"]');
            fName.addEventListener('input', () => {
                // Get references to selected style, selected icon, and first name elements
                const selectedStyle = document.querySelector(".selected_style");
                const selectedIcon = document.querySelector(".selected_icon");
                const firstName = document.querySelector('[name="first_name"]');
                const selectedType = document.querySelector('.selected_type');
    
                // Check if all required fields are filled
                if (
                    selectedStyle.textContent.trim() &&
                    selectedIcon.textContent.trim() &&
                    firstName.value.trim()
                ) {
                    document.querySelector(".product-single__add-to-cart").innerHTML = mainAtcButton;
                }
    
                // Check if first name input has content and show/hide error
                if (fName.value) {
                    removeError(fName);
                } else {
                    checkForATCButton()
                    showError(fName);
                }
            });
    
            // Check for touch support and add the appropriate event listener
            if ('ontouchstart' in window) {
                document.querySelector('.product-one').addEventListener('touchstart', function(event) {
                    handleButtonClick(event);
                });
            } else {
                document.querySelector('.product-one').addEventListener('mouseover', function(event) {
                    handleButtonClick(event);
                });
            }
    
            // Function to handle button click
            function handleButtonClick(event) {
                const lastName = inputLastName.value;
                const selectedStyle = document.querySelector(".selected_style");
                const selectedIcon = document.querySelector(".selected_icon");
                const firstName = document.querySelector('[name="first_name"]');
                const selectedType = document.querySelector('.selected_type');
    
                // Check if all required fields are filled
                if (
                    selectedStyle.textContent.trim() &&
                    selectedIcon.textContent.trim() &&
                    firstName.value.trim()
                ) {
                    document.querySelector(".product-single__add-to-cart").innerHTML = mainAtcButton;
    
                    // Update hidden form fields if all required fields are filled
                    // typeCapturer.value = `${selectedTypeVariantOption}`;
                    styleCapturer.value = `${selectedStyleVariantOption}`;
                    iconCapturer.value = `${selectedSymbolVariantOption}`;
                    nameCapturer.value = `${firstName.value}`;
                    enameCapturer.value = `${lastName}`;
                }
            }
    
            // Checking and replacing ATC button to make it work wtih click event
            function checkForATCButton() {
                const atcButton = document.querySelector('.product-single__add-to-cart'); // Replace with the actual selector for the new ATC button
    
                if (atcButton) {
                    // The ATC button is found, you can now work with it
                    // Set the initial HTML content of the "Add to Cart" button
                    document.querySelector(".product-single__add-to-cart").innerHTML = `<a class="btn btn--primary btn--add-to-cart full">
            <span class="btn__text">
              <span class="material-icons-outlined button-cart-icon">local_mall</span>
              <span class="btn__add-to-cart-text">Add to Cart</span>
            </span>
          </a>`;
                    // Perform any actions you need with the button here
                } else {
                    // The ATC button is not found yet, continue checking
                    setTimeout(checkForATCButton, 1000); // Check again in 1 second (adjust the timing as needed)
                }
            }
    
            // Start checking for the ATC button when the page loads
            window.addEventListener('load', checkForATCButton);
    
            // Add a click event listener to the "Add to Cart" button
            document.addEventListener('click', function(event) {
                const clickedElement = event.target;
    
                // Check if the clicked element or its ancestors have the class 'btn--add-to-cart'
                let isButtonClick = false;
                let currentElement = clickedElement;
    
                while (currentElement) {
                    if (currentElement.classList.contains('btn--add-to-cart')) {
                        isButtonClick = true;
                        break;
                    }
                    currentElement = currentElement.parentElement;
                }
    
                if (isButtonClick) {
                    // The click occurred on an element with the class 'btn--add-to-cart' or one of its ancestors
    
                    const lastName = inputLastName.value;
                    const selectedStyle = document.querySelector(".selected_style");
                    const selectedIcon = document.querySelector(".selected_icon");
                    const firstName = document.querySelector('[name="first_name"]');
    
                    // Validate selected fields and display errors if necessary
                  
                   if(!document.querySelector('.pl-variant-options.type .pl-variant-option.border')) {
                     showError(document.querySelector('span.selected_type'));
                   } else if (selectedStyle.textContent.trim() === "") {
                        showError(selectedStyle);
                    } else if (selectedIcon.textContent.trim() === "") {
                        showError(selectedIcon);
                    } else if (firstName.value.trim() === "") {
                        showError(firstName);
                    }
    
    
                }
            });
    
            // Clear the interval once the necessary elements are found
            clearInterval(myInterval);
        }
    }, 1000);
    
    // Function to remove error messages
    function removeError(targetElement) {
        if (
            targetElement.tagName == "INPUT" &&
            targetElement.previousElementSibling.tagName == "LABEL" &&
            targetElement.previousElementSibling.innerHTML.includes(
                "This Field Is Required"
            )
        ) {
            targetElement.previousElementSibling.firstElementChild.remove();
        }
        if (targetElement.innerHTML.includes("This Field Is Required")) {
            targetElement.textContent = "";
        }
    }
    
    // Function to show error messages
    function showError(targetElement) {
        if (
            targetElement.tagName == "INPUT" &&
            targetElement.previousElementSibling.tagName == "LABEL" && !targetElement.previousElementSibling.innerHTML.includes(
                "This Field Is Required"
            )
        ) {
            targetElement.previousElementSibling.innerHTML = `${targetElement.previousElementSibling.textContent} <span style = 'color: #e54545' > * This Field Is Required! </span>`;
            const headerHeight = 106; // Replace with your actual header height
    
            if (targetElement) {
                const elementTop = targetElement.getBoundingClientRect().top;
                const isElementVisible = elementTop >= headerHeight && elementTop < window.innerHeight;
    
                if (!isElementVisible) {
                    const targetPosition = elementTop + window.scrollY - headerHeight;
    
                    window.scrollTo({
                        top: targetPosition,
                        behavior: 'smooth'
                    });
                }
            }
    
        } else {
            targetElement.innerHTML =
                "<span style='color: #e54545'> * This Field Is Required! </span>";
            const headerHeight = 106; // Replace with your actual header height
    
            if (targetElement) {
                const elementTop = targetElement.getBoundingClientRect().top;
                const isElementVisible = elementTop >= headerHeight && elementTop < window.innerHeight;
    
                if (!isElementVisible) {
                    const targetPosition = elementTop + window.scrollY - headerHeight;
    
                    window.scrollTo({
                        top: targetPosition,
                        behavior: 'smooth'
                    });
                }
            }
        }
    }
    
      // select function to add borders
    
      addBorder(styleDSSVariantOptions);
      addBorder(typeVariantOptions);
      addBorder(styleVariantOptions);
      addBorder(symbolVariantOptions);
    
      //================= setting preview callback
      // for Style and Icon
    
      setPreview(stylePreview, styleDSSVariantOptions);
      setPreview(stylePreview, styleVariantOptions);
      setPreview(symbolPreview, symbolVariantOptions);
    
      // for input values
    
      setText(textWrapperFirstName, inputFirstName);
      setText(textWrapperLastName, inputLastName);
    }
    
    // add additional product here getting the style value here
    
    getVal('product-one')
      
    function removeBorder(el) {
      el.forEach((e) => {
        e.classList.remove('border');
      });
    }
    
    function addBorder(el) {
      el.forEach((e) => {
        e.addEventListener('click', () => {
          removeBorder(el);
          e.classList.add('border');
        });
      });
    }
    
    // actual preview funtion for icon and stamp. callback used in getVal function above
    
    function setPreview(item, values) {
      values.forEach((value, index) => {
        value.addEventListener('click', () => {
          if (index != 23) {
            var getStyle = value.getAttribute('style');
            item.setAttribute('style', `${getStyle}`);
          } else {
            item.setAttribute('style', `background: white;`);
          }
        });
      });
    }
    // actual preview funtion for inputs. callback used in getVal function above
    
    function setText(item, values) {
      values.addEventListener('input', () => {
        item.innerHTML = `<p class="prev_child">${values.value}</p>`;
      });
    }
    
    let singleSidedStamp = document.querySelector('[data-name="Single-sided stamp (black ink only)"]')
    let doubleSidedStamp = document.querySelector('[data-name="Double-sided stamp (black & white ink)"]')
    let dssParent = document.querySelector('.styleDSS-parent')
    let styleParent = document.querySelector('.style-parent')
      
    
    singleSidedStamp.addEventListener('click', () => {
      dssParent.style.display = 'none'
      styleParent.style.display = 'block'
    
      // For normal use
          document.querySelector('[data-option-1="Single-sided stamp (black ink only)"]').selected=true
      
      // It's for Gempages
        // document.querySelectorAll('.gf_swatches-selector .gf_swatch')[0].click()
    })
    
    doubleSidedStamp.addEventListener('click', () => {
      dssParent.style.display = 'block'
      styleParent.style.display = 'none'
    
      // For normal use
          document.querySelector('[data-option-1="Double-sided stamp (black & white ink)"]').selected=true
      
      // It's for Gempages
      // document.querySelectorAll('.gf_swatches-selector .gf_swatch')[1].click()
    })
    
    
    
      // Code for countdown timer
    
      // Set the initial countdown duration (7 hours and 14 minutes in milliseconds)
    let countdownDuration = 7 * 60 * 60 * 1000 + 14 * 60 * 1000;
    
    const priceContainer = document.querySelector('.price-container span#ComparePrice')
    priceContainer.insertAdjacentHTML("afterend", `<p id="discountCountdown">🚀 Launch Price - <span style="color: #38b6ff;">20%  OFF</span> ⚡️ | ⏰ <span style="    color: #38b6ff;">
    <span id="hours"></span>hrs <span id="min"></span> min
    </span> left ⌛️</p>`)
      
    function updateCountdown() {
      // Calculate the remaining hours and minutes
      let hours = Math.floor(countdownDuration / (1000 * 60 * 60));
      let minutes = Math.floor((countdownDuration % (1000 * 60 * 60)) / (1000 * 60));
      
     
      // Display the countdown
      document.getElementById("hours").textContent = hours
      document.getElementById("min").textContent = minutes
    
      // Update the countdown duration
      countdownDuration -= 1000;
    
      // Check if the countdown has reached zero
      if (countdownDuration < 0) {
        // Reset the countdown to 7 hours and 14 minutes
        countdownDuration = 7 * 60 * 60 * 1000 + 14 * 60 * 1000;
      }
    
      // Update the countdown every second
      setTimeout(updateCountdown, 1000);
    }
    
    // Call the updateCountdown function to start the countdown
    updateCountdown();
    
    
     let comparePrice=document.querySelector('span#ComparePrice').textContent 
    
    
    const Customfields2 = setInterval(() => {
        if(document.querySelector(".pl-variant-options.type .pl-variant-option:last-child") && document.querySelector(".pl-variant-options.type .pl-variant-option:first-child")) {
    
            
    document.querySelector(".pl-variant-options.type .pl-variant-option:last-child").addEventListener("click", (e) => {
        // console.log(e)
     
      document.querySelector('span#ComparePrice').textContent = 'Was '+comparePrice
      
      document.getElementById("discountCountdown").style.display="block"
        document.querySelector('span#ComparePrice').style.display="block"
        
      
      
      });
    
    document.querySelector(".pl-variant-options.type .pl-variant-option:first-child").addEventListener("click", (e) => {
        console.log(e)
        document.getElementById("discountCountdown").style.display="none"
      
      document.querySelector('span#ComparePrice').style.display="none"
      });
            clearInterval(Customfields2);
    
        }
    
    }, 1000);
    
    
      
    </script>
