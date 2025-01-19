

# PROJET OHMYFOOD

## ASSETS/ : IMAGES ET LOGOS

## CSS/ : STYLES CSS COMPILéS
=> NE JAMAIS Y TOUCHER
=> SAUF SI BUG SUR LES STYLES : SUPPRIMER LE DOSSIER COMPLET (css/)

## RESTAURANTS/
=> PAGES DES RESTAURANTS (HTML x4)

## SASS/
=> les fichiers _index.scss servent à importer tous les fichiers présents dans le dossier
=> les "_" (underscores) servent à dire au compilateur `sass --watch sass:css` qu'il ne faut pas compiler ces fichiers

### base/
- _reset.scss : remise à zéro des styles du navigateur par défault (pour éviter les conflits de styles)
- base.scss : pour y mettre tous les styles de base du site (exemple : la couleur par défaut des liens, les styles du body (background))

### components/
- navbar
- 

### layout/
### utils/
 @include heart($font-weight-thin, $color-canvas-inverted, $font-size-l, $font-weight-bold);border: 16px solid #f3f3f3;
        

         .loader-container{
      background-color: #F3F3F3;
      animation:fond ease 3s;
    }
    @keyframes fond {
      0% {opacity:1;}
      100%{ opacity:0;}
    }
    .loader {
        border: 16px solid #F3F3F3;
        border-top: 16px solid $color-secondaire;
        border-radius: 50%;
        width: 120px;
        height: 120px;
        animation: spin 4s linear;
        position: fixed;
        z-index: 1;
        opacity: 0;
        top: 50%;
        left:46%
      }
      @keyframes spin {
        0% {
          opacity: 1;
          transform: rotate(0deg);
        }
        100% {opacity: 0;
          transform: rotate(360deg);
        }
      }
    