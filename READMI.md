### Header: Fix bug UI Phần 1

## Navbar font-size:

- font-size: 1.4rem -> 1.3rem
  -> done

## Navbar social-icons:

- .header\_\_navbar-icon-link:nth-child(2) -> margin-left: 3px
  -> done

## Navbar bell-icon and margin:

- i.fa-regular.fa-circle-question -> margin-right: 3px;
  -> done

## Notification arrow-top offset + z-index + border-radius:

- .header\_\_notify -> transform-origin: calc(100% - 32px) top
  -> z-index: 1
  -> border-radius: 2px
  -> done

## Navbar margin between avatar and name:

- .header\_\_navbar-user-name -> margin-left: 4px
  -> done

## User menu separate:

- Add ".header\_\_navbar-user-item--separate" for ".header\_\_navbar-user-item"
- .header\_\_navbar-user-item:hover
  -> background-color: #f5f5f5;
  -> cursor: pointer;
- .header\_\_navbar-user-item--separate -> border-top: 1px solid rgba(0,0,0,0.05);

-> done

## Logo link:

- Add ".header**logo-link" bỞc "header**logo-img"
- .header\_\_logo-link -> text-decoration: none, color: transparent
  -> done

## Search selection offset-top:

- -> done

### App-Container: Fix bug UI Phần 2:

## Header QR code z-index:

->" .header\_\_QR " -> box-shadow: 0 1px 2px rgba(0,0,0,0.1)
-> z-index: 1;

-> done

## User menu offset-top:

-> ".header\_\_navbar-user-menu::before" -> top: -28px;

-> done

## Search history z-index:

-> ".header\_\_search-history" -> z-index = 1

-> done

## Search selection z-index:

-> ".header\_\_search-option" -> z-index = 1

-> done

## Cart z-index + cart quantity:

-> ".header**cart-list" -> z-index = 1
-> ".header**cart-list-item " -> height: 50vh , overflow-y: auto;

-> done

## Cart Product name limiting:

-> Khi thông tin quá dài ".header**cart-item-name"
-> line-height: 2rem;
max-height:4rem;
overflow: hidden;
flex: 1;
padding-right: 16px;
display: -webkit-box;
-webkit-box-orient: vertical;
-webkit-line-clamp: 2;
text-align: left;
-> ".header**cart-item-head" ->
flex = 1,

-> done

## Category style: Add border-top

->".category-item " -> position: relative;

-> ".category-item:first-child::before" -> display: none;

-> ".category-item-link" -> padding: 10px 16px;

-> done

## Product border-radius:

-> ".home-product-item" -> Remove and Fix all -> border-radius: 2px

-> ".home-product-item\_\_img" -> border-top-left-radius: 2px, border-top-right-radius: 2px

-> ".home-product-item\_\_sale-off " -> border-top-right-radius: 2px;
