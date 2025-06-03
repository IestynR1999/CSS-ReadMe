<h3>CSS</h3>

```CSS
//Version 1.2

.pagelevelprogress__indicator-inner {
border-radius: 0px; 
}

.pagelevelprogress__nav-btn {
    pointer-events: none;
}

//Hotgraphic Pins

#wrapper .page .hotgraphic .hotgraphic__inner .hotgraphic__widget.is-pin .hotgraphic__pin-item .hotgraphic__pin, #wrapper .page .hotgraphic .hotgraphic__inner .hotgraphic__widget.is-pin .hotgraphic__pin-item .hotgraphic__pin .icon
 {
    border-radius: 50%;
    background-color: transparent;
    height: 80px;
    width: 80px;
}

@media (max-width:1023px){
     #wrapper .page .hotgraphic .hotgraphic__inner .hotgraphic__widget.is-pin .hotgraphic__pin-item .hotgraphic__pin, #wrapper .page .hotgraphic .hotgraphic__inner .hotgraphic__widget.is-pin .hotgraphic__pin-item .hotgraphic__pin .icon {
    border-radius: 50%;
    background-color: transparent;
    height: 65px;
    width: 65px;
}
}

//Graphic padding  
 
.graphic-padding-right-left-20 {
    padding-left: 20px;
    padding-right: 20px;
}  
 
.graphic-padding-right-left-40 {
    padding-left: 40px;
    padding-right: 40px;
}  
 
.graphic-padding-right-left-60 {
    padding-left: 60px;
    padding-right: 60px;
}
.graphic-padding-right-left-80 {
    padding-left: 80px;
    padding-right: 80px;
}
.graphic-padding-right-left-100 {
    padding-left: 100px;
    padding-right: 100px;
}
.graphic-padding-right-left-120 {
    padding-left: 120px;
    padding-right: 120px;
}
.graphic-padding-right-left-140 {
    padding-left: 140px;
    padding-right: 140px;
}
.graphic-padding-top-20 {
    padding-top: 20px;
}
 
.graphic-padding-top-40 {
    padding-top: 40px;
}
 
.graphic-padding-top-60 {
    padding-top: 60px;
}
 
.graphic-padding-top-80 {
    padding-top: 80px;
}
 
.graphic-padding-bottom-20 {
    padding-bottom: 20px;
}
 
.graphic-padding-bottom-40 {
    padding-bottom: 40px;
}
 
.graphic-padding-bottom-60 {
    padding-bottom: 60px;
}
 
.graphic-padding-bottom-80 {
    padding-bottom: 80px;
}

//sagnik code

#adapt #app #wrapper .component__inner .assetlink:hover, 
#adapt #app #wrapper .component__inner .customlink:hover{
    color: unset !important;
}

.page .article-edge-top {
    background-attachment: scroll;
    background-position: center top;
    background-size: 100% 100%;
}
.page .article-edge-bottom {
    background-attachment: scroll;
    background-position: center bottom;
    background-size: 100% 100%;
}

.component__instruction{
    margin-bottom:12px;
}

//adding spacing between each block where there are multiple blocks
.block__container .block + .block {
    margin-top:2.75rem;
}

//rempving spacing between each block where there are multiple blocks in Assessments
.is-assessment .block__container .block + .block {
    margin-top:0;
}

.downArrow{
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    z-index:1;
    bottom:-70px;
}

.text__body-inner{
    display: flex;
    flex-direction: column;
}

.divider{
    height: 1px;
    width:100%;
    margin: 12px 0;
}

.no-padding-backgrounds .component .component__body{
    padding:0 !important;
}

.no-padding-backgrounds .component__title,
.no-padding-backgrounds .component__title * {
    padding:0 !important;
    margin:0 !important;
    font-family: FSDillonProBold !important;
    font-size:1.669rem !important;
    line-height: 2.25rem !important; 
    letter-spacing: 0.002rem !important;
}

.background-colour1 .divider{
    background: linear-gradient(180deg, #CED1DA 0%, #D7DCEA 100%);
}

.background-colour2 .divider{
    background: linear-gradient(180deg, #5F5F5F 0%, #403F3F 98.77%);
}

//remove later
.hero .block__inner, .heroShallow .block__inner{
    position:relative;
}

.Module-Hero .block__inner, .Topic-Hero .block__inner{
    position:relative;
}

.heroDescription{
    padding:0 15%;
    font-family: FSDillonProRegular !important;
    font-size: 1.25rem !important;
}

.Body-Regular{
    font-family: 'FSDillonProRegular' !important;
    //font-size: 1.25rem !important;
}

.Module-Hero .Body-Regular{
    padding:0 15%;
}

.Topic-Hero .Body-Regular{
   margin:0;
   padding:0;
}

//remove later
.heroShallow .heroDescription{
    margin:0;
    padding:0;
}

.Topic-Hero .Body-Regular{
    margin:0;
    padding:0;
}

.btn__action.is-disabled,
.btn__action.is-disabled:hover,
.btn__action.is-disabled:focus{
    color: #515D7A !important;
    background-color: #E9EBF1 !important;
}

.background-colour1 .btn__feedback.is-disabled, 
.background-colour2 .btn__feedback.is-disabled,
.background-colour1 .btn__feedback.is-disabled:hover, 
.background-colour2 .btn__feedback.is-disabled:hover,
.background-colour1 .btn__feedback.is-disabled:focus, 
.background-colour2 .btn__feedback.is-disabled:focus{
    color: #AAB0C0 !important;
    background-color: #FFFFFF !important;
    border:2px solid #E9EBF1 !important;
}

//testing border override
#adapt #wrapper .btn__response-container button:focus {
    border:2px solid #E9EBF1 !important;
}

.btn__response-container button{
    padding: 1rem 0 !important;
}

.btn__feedback,.btn__feedback:hover,.btn__feedback:focus {
    border:2px solid #AEBDE6 !important;
    background-color:transparent !important;
    font-family: FSDillonProBold !important;
    font-size: 1em !important;
}

.background-colour1 .btn__feedback,
.background-colour1 .btn__feedback:hover,
.background-colour1 .btn__feedback:focus
{
    color:#041C39 !important;
}

.background-colour2 .btn__feedback,
.background-colour2 .btn__feedback:hover,
.background-colour2 .btn__feedback:focus
{
    color:#FFFFFF !important;
}

.btn__action,.btn__action:hover,.btn__action:focus{
    font-family: FSDillonProBold !important;
    font-size: 1rem !important;
    background-color:#DD221A !important;
}

.assessmentresults__retry-btn,.assessmentresults__retry-btn:hover,.assessmentresults__retry-btn:focus{
    font-family: FSDillonProBold !important;
    font-size: 1rem !important;
    background-color:#DD221A !important;
    line-height: 1.25rem !important;
    letter-spacing: 0.02rem !important;
    color: #FFF !important;
    margin-top: 1.25rem !important;
}

//remove later
.hero,.heroShallow {
    //background-size: 100% 100% !important;
    background-size: cover !important;
    background-position: center !important;
    background-repeat:no-repeat !important;
    background-color:#e9ebf1!important;
    position:relative;
}

.Module-Hero, .Topic-Hero{
    background-size: cover !important;
    background-position: center !important;
    background-repeat:no-repeat !important;
    background-color:#e9ebf1!important;
    position:relative;
}

//.hero .HeaderPadding{
//remove later
.HeaderPadding {
    padding-bottom: 70px;
    padding-top: 70px;
}

.Module-Hero .block,
.Topic-Hero .block{
    padding-bottom: 70px;
    padding-top: 70px;
}

//remove later
.hero .article__inner, .heroShallow .article__inner{
    padding:0 !important;
}

.Module-Hero .article__inner, .Topic-Hero .article__inner{
    padding:0 !important;
}

div.component {
    margin-bottom: 0;
}
#adapt #wrapper.location-menu.cinnamonmenu .menu-item.is-locked .menu-item__inner {
    text-align: left;
}
// ---------------------------------------------------------
// Rounded Corners
// ---------------------------------------------------------

.pagefooternavigation__btn {
    border-radius: 4px;
}


.narrative .narrative__inner .narrative__controls {
    border-radius: 4px;
}

//------------------------------------------------------------------------------
//HOT GRAPHIC-------------------------------------------------------------------
//------------------------------------------------------------------------------

.hotgraphic__pin{
    padding:0 !important;
}
.notify.hotgraphic .notify__popup .notify__content .hotgraphic-popup {
    box-shadow:0px 151px 42px 0px rgba(0, 0, 0, 0.00), 0px 97px 39px 0px rgba(0, 0, 0, 0.02), 0px 54px 33px 0px rgba(0, 0, 0, 0.06), 0px 24px 24px 0px rgba(0, 0, 0, 0.10), 0px 6px 13px 0px rgba(0, 0, 0, 0.12)
}

.notify.hotgraphic .notify__popup .notify__content .hotgraphic-popup__inner {
    border-bottom-left-radius: 4px;
    border-bottom-right-radius: 4px;
}

.notify.hotgraphic .notify__popup .notify__content .hotgraphic-popup__toolbar {
    border-top-left-radius: 4px;
    border-top-right-radius: 4px;
    //background-color: #323231 !important;
    background-color: #404040 !important;
}

.notify.hotgraphic .hotgraphic-popup__count {
    font-family: 'FSDillonProRegular' !important;
    font-size: 1rem !important;
    letter-spacing: 0.015rem !important;
}

.hotgraphic-popup__item-title-inner{
    font-family: 'FSDillonProBold' !important;
    font-size: 1.66rem!important;
    line-height: 2.25rem !important;
    letter-spacing: 0.002rem !important;
    color: #041C39 !important;
}

.hotgraphic-popup__item-body-inner span,
.hotgraphic-popup__item-body-inner li,
.hotgraphic-popup__item-body-inner ul,
.hotgraphic-popup__item-body-inner div,
.hotgraphic-popup__item-body-inner p{
    font-family: 'FSDillonProRegular' !important;
    color:#4F6074 !important;
    font-size:1.25rem !important;
    line-height:1.5rem !important;
}

.hotgraphic-popup__item-body-inner ul,
.hotgraphic-popup__item-body-inner p{
     margin:0.25rem 0 !important;
}


.notify.hotgraphic .notify__popup .notify__content .hotgraphic-popup__toolbar .btn-icon,
#adapt .notify__popup:not(.is-bookmarking) .notify__popup-inner button,
.notify.hotgraphic .notify__popup .notify__content .hotgraphic-popup__toolbar .btn-icon:hover,
#adapt .notify__popup:not(.is-bookmarking) .notify__popup-inner button:hover
{
    background: transparent !important;
}

.notify.hotgraphic .notify__popup .notify__content .hotgraphic-popup__toolbar .btn-icon:not(.is-disabled) .icon,
#adapt .notify__popup .notify__popup-inner button:not(.is-disabled) .icon{
   color:#ffffff !important; 
}

#adapt .notify__popup .notify__popup-inner button.hotgraphic-popup__controls .icon:before{
    font-size:2rem !important;
}


.flipcard .flipcard__item-back {
    background-color:#F0F1F4 !important;
    display: flex;
    flex-direction: column;
    justify-content: center;
}


.flipcard .flipcard__item-back-title {
    font-size: 1.67rem;
    font-style: normal;
    font-weight: 700;
    line-height: 2.25rem;
    letter-spacing: 0.002rem;
    font-family: FSDillonProBold !important;
    color:#041C39 !important;
}

.flipcard .flipcard__item-back-body p,
.flipcard .flipcard__item-back-body ul,
.flipcard .flipcard__item-back-body li
{
    font-size: 1.25rem !important;
    font-style: normal !important;
    font-weight: 400 !important;
    line-height: 1.25rem !important;
    letter-spacing: 0.02rem !important;
    color:#4F6074 !important;
    font-family: 'FSDillonProRegular' !important;
}

.flipcard .flipcard__item-back-body > p{
   margin:0.25rem 0 !important; 
}

.hiddenHotspots .component__title,
.accordion .component__title,
.imagegallery .component__title,
.reveal .component__title,
.matching .component__title,
.branching .component__title,
.assesmentResults .component__title,
.narrativeContainer .component__title,
.graphicContainer .component__title,
.mediaContainer .component__title,
.truefalseContainer  .component__title,
.truefalseContainer  .component__title,
.flipcard .component__title,
.hotgraphic .component__title,
.hotGraphicContainer .component__title,
.sliderContainer .component__title,
{
    background: transparent !important;
    padding: 0 !important;
}

//Open components
.accordion .component__title *,
.imagegallery .component__title *,
.referenceList .component__title *,
.reveal .component__title *,
.branching .component__title *,
.assesmentResults .component__title *,
.narrativeContainer .component__title *,
.graphicContainer .component__title *,
.mediaContainer .component__title *,
.hotgraphic .component__title *,
.hotGraphicContainer .component__title *,
{
    padding: 0 !important;
    margin: 0 !important;
    font-family: FSDillonProBold !important;
    font-style: normal !important;
    //font-size: 2.221rem !important;
    //font-size: 2.22rem !important;
    //line-height: 2.5rem !important;
    //letter-spacing: 0.004rem !important;
    //font-size:1.669rem !important;
    font-size:clamp(1.669rem, 1.669rem + 0vw, 1.669rem) !important;
    //line-height: 2.25rem !important; 
    line-height:clamp(1.5rem, 1.4049rem + 4.2254vw, 2.25rem) !important;
    letter-spacing: 0.002rem !important;
}

//Box components
.hiddenHotspots .component__title *,
.matching .component__title *,
.sliderContainer .component__title *,
.flipcard .component__title *{
    padding: 0 !important;
    margin: 0 !important;
    font-style: normal !important;
    font-family: FSDillonProBold !important;
    //font-size:1.669rem !important;
    font-size:clamp(1.669rem, 1.669rem + 0vw, 1.669rem) !important;
    //line-height: 2.25rem !important; 
    line-height:clamp(2.25rem, 2.25rem + 0vw, 2.25rem) !important;
    letter-spacing: 0.002rem !important;
}

.hiddenHotspots .component__header-inner,
.accordion .component__header-inner,
.imagegallery .component__header-inner,
.reveal .component__header-inner,
.matching .component__header-inner,
.branching .component__header-inner,
.assesmentResults .component__header-inner,
.narrativeContainer .component__header-inner,
.graphicContainer .component__header-inner,
.mediaContainer .component__header-inner,
.sliderContainer .component__header-inner,
.truefalseContainer .component__header-inner,
.flipcard .component__header-inner,
.hotgraphic .component__header-inner,
.hotGraphicContainer .component__header-inner,
{
    display: flex;
    flex-direction: column;
    gap: 0.75rem;
}

.stackerContainer .component__body,
.hiddenHotspots .component__body,
.textinput .component__body,
.accordion .component__body,
.imagegallery .component__body,
.reveal .component__body,
.matching .component__body,
.branching .component__body,
.assesmentResults .component__body,
.graphicalMCQ .component__body,
.filInBlanksContainer .component__body,
.narrativeContainer .component__body,
.graphicContainer .component__body,
.mediaContainer .component__body,
.mcqContainer .component__body,
.sliderContainer .component__body,
.truefalseContainer .component__body,
.flipcard .component__body,
.hotgraphic .component__body,
.hotGraphicContainer .component__body,
{
    padding:0 !important;
    margin:0 !important;
    background: transparent !important;
}

.stackerContainer .component__body .component__body-inner,
.hiddenHotspots .component__body .component__body-inner,
.accordion .component__body .component__body-inner,
.imagegallery .component__body .component__body-inner,
.reveal .component__body .component__body-inner,
.matching .component__body .component__body-inner,
.branching .component__body .component__body-inner,
.assesmentResults .component__body .component__body-inner,
.graphicalMCQ .component__body .component__body-inner,
.filInBlanksContainer .component__body-inner,
.narrativeContainer .component__body-inner,
.graphicContainer .component__body-inner,
.mediaContainer .component__body-inner,
.mcqContainer .component__body-inner,
.sliderContainer .component__body-inner,
.truefalseContainer .component__body-inner,
.flipcard .component__body-inner,
.hotgraphic .component__body-inner,
.hotGraphicContainer  .component__body-inner,
{
    padding:0 !important;
    margin:0 !important;
}

.textinput .component__body .component__body-inner{
   padding: 0 0 .75rem 0 !important; 
}

.stackerContainer .component__body-inner p,
.hiddenHotspots .component__body-inner p,
.textinput .component__body-inner p,
.accordion .component__body-inner p,
.imagegallery .component__body-inner p,
.reveal .component__body-inner p,
.matching .component__body-inner p,
.branching .component__body-inner p,
.assesmentResults .component__body-inner p,
.narrativeContainer .component__body-inner p,
.graphicContainer .component__body-inner p,
.mediaContainer .component__body-inner p,
.sliderContainer .component__body-inner p,
.truefalseContainer .component__body-inner p,
.flipcard .component__body-inner p,
.hotgraphic .component__body-inner p,
.hotGraphicContainer .component__body-inner p,
{
    font-family: 'FSDillonProRegular' !important;
    //font-size: 1.25rem;
    font-size:clamp(1.25rem, 1.25rem + 0vw, 1.25rem);
    font-style: normal;
    font-weight: 400;
    //line-height:1.5rem;
    line-height:clamp(1.5rem, 1.5rem + 0vw, 1.5rem) !important;
    letter-spacing: 0.02rem;
    margin:0 !important;
}

.background-colour1 .stackerContainer .component__body-inner p,
.background-colour1 .hiddenHotspots .component__body-inner p,
.background-colour1 .textinput .component__body-inner p,
.background-colour1 .accordion .component__body-inner p,
.background-colour1 .imagegallery .component__body-inner p,
.background-colour1 .referencelist .component__body-inner p,
.background-colour1 .reveal .component__body-inner p,
.background-colour1 .matching .component__body-inner p,
.background-colour1 .branching .component__body-inner p,
.background-colour1 .assesmentResults .component__body-inner p,
.background-colour1 .narrativeContainer .component__body-inner p,
.background-colour1 .graphicContainer .component__body-inner p, 
.background-colour1 .mediaContainer .component__body-inner p, 
.background-colour1 .sliderContainer .component__body-inner p, 
.background-colour1 .truefalseContainer .component__body-inner p, 
.background-colour1 .flipcard .component__body-inner p,
.background-colour1 .hotGraphicContainer .component__body-inner p{
    color:#4F6074;
}

.background-colour2 .stackerContainer .component__body-inner p,
.background-colour2 .hiddenHotspots .component__body-inner p,
.background-colour2 .textinput .component__body-inner p,
.background-colour2 .accordion .component__body-inner p,
.background-colour2 .imagegallery .component__body-inner p,
.background-colour2 .referencelist .component__body-inner p,
.background-colour2 .reveal .component__body-inner p,
.background-colour2 .matching .component__body-inner p,
.background-colour2 .branching .component__body-inner p,
.background-colour2 .assesmentResults .component__body-inner p,
.background-colour2 .narrativeContainer .component__body-inner p,
.background-colour2 .graphicContainer .component__body-inner p,
.background-colour2 .mediaContainer .component__body-inner p, 
.background-colour2 .sliderContainer .component__body-inner p,
.background-colour2 .truefalseContainer .component__body-inner p,
.background-colour2 .flipcard .component__body-inner p,
.background-colour2 .hotGraphicContainer .component__body-inner p{
    color:#E9EBF1;
}

.text .component__instruction-inner:after,
.stackerContainer .component__instruction-inner:after,
.hiddenHotspots .component__instruction-inner:after,
.textinput .component__instruction-inner:after,
.accordion .component__instruction-inner:after,
.imagegallery .component__instruction-inner:after,
.referencelist .component__instruction-inner:after,
.reveal .component__instruction-inner:after,
.matching .component__instruction-inner:after,
.branching .component__instruction-inner:after,
.mcqContainer .component__instruction-inner:after,
.filInBlanksContainer .component__instruction-inner:after,
.narrativeContainer .component__instruction-inner:after,
.graphicContainer .component__instruction-inner:after,
.mediaContainer .component__instruction-inner:after,
.sliderContainer .component__instruction-inner:after,
.truefalseContainer .component__instruction-inner:after,
.flipCardContainer .component__instruction-inner:after,
.hotGraphicContainer .component__instruction-inner:after
{
    border:none;
    height:1px;
    content: '';
    display: block;
    left: 0;
    position: absolute;
    top: 0;
    width: 100%;
}

.background-colour1 .text .component__instruction-inner:after,
.background-colour1 .stackerContainer .component__instruction-inner:after,
.background-colour1 .hiddenHotspots .component__instruction-inner:after,
.background-colour1 .textinput .component__instruction-inner:after,
.background-colour1 .accordion .component__instruction-inner:after,
.background-colour1 .imagegallery .component__instruction-inner:after,
.background-colour1 .referencelist .component__instruction-inner:after,
.background-colour1 .reveal .component__instruction-inner:after,
.background-colour1 .matching .component__instruction-inner:after,
.background-colour1 .branching .component__instruction-inner:after,
.background-colour1 .mcqContainer .component__instruction-inner:after,
.background-colour1 .filInBlanksContainer .component__instruction-inner:after,
.background-colour1 .narrativeContainer .component__instruction-inner:after,
.background-colour1 .graphicContainer .component__instruction-inner:after,
.background-colour1 .mediaContainer .component__instruction-inner:after,
.background-colour1 .sliderContainer .component__instruction-inner:after,
.background-colour1 .truefalseContainer .component__instruction-inner:after,
.background-colour1 .flipCardContainer .component__instruction-inner:after,
.background-colour1 .hotGraphicContainer .component__instruction-inner:after{
     background:linear-gradient(180deg, #CED1DA 0%, #D7DCEA 100%);
}

.background-colour2 .text .component__instruction-inner:after,
.background-colour2 .stackerContainer .component__instruction-inner:after,
.background-colour2 .hiddenHotspots .component__instruction-inner:after,
.background-colour2 .textinput .component__instruction-inner:after,
.background-colour2 .accordion .component__instruction-inner:after,
.background-colour2 .imagegallery .component__instruction-inner:after,
.background-colour2 .referencelist .component__instruction-inner:after,
.background-colour2 .reveal .component__instruction-inner:after,
.background-colour2 .matching .component__instruction-inner:after,
.background-colour2 .branching .component__instruction-inner:after,
.background-colour2 .mcqContainer .component__instruction-inner:after,
.background-colour2 .filInBlanksContainer .component__instruction-inner:after,
.background-colour2 .narrativeContainer .component__instruction-inner:after,
.background-colour2 .graphicContainer .component__instruction-inner:after,
.background-colour2 .mediaContainer .component__instruction-inner:after,
.background-colour2 .sliderContainer .component__instruction-inner:after,
.background-colour2 .truefalseContainer .component__instruction-inner:after,
.background-colour2 .flipCardContainer .component__instruction-inner:after,
.background-colour2 .hotGraphicContainer .component__instruction-inner:after{
    background:linear-gradient(180deg, #5F5F5F 0%, #403F3F 98.77%);
}

//.text .component__instruction,
.stackerContainer .component__instruction,
.hiddenHotspots .component__instruction,
.textinput .component__instruction,
.accordion .component__instruction,
.imagegallery .component__instruction,
.reveal .component__instruction,
.matching .component__instruction,
.branching .component__instruction,
.assesmentResults .component__instruction,
.filInBlanksContainer .component__instruction,
.narrativeContainer .component__instruction,
.graphicContainer .component__instruction,
.mediaContainer .component__instruction,
.sliderContainer .component__instruction,
.truefalseContainer .component__instruction,
.flipCardContainer .component__instruction,
.hotGraphicContainer .component__instruction{
    background:transparent !important;
}

.hiddenHotspots .component__widget,
.accordion .component__widget,
.reveal .component__widget,
.branching .component__widget,
.graphicContainer .component__widget,
.flipCardContainer .component__widget,
.hotGraphicContainer .component__widget{
    //margin-top: 1.75rem;
    margin-top: 1.25rem;
}
//------------------------------------------------------------------------------
//--------TRUE OR FALSE---------------------------------------------------------
//------------------------------------------------------------------------------

.truefalse__item-container{
    padding:0 !important;
    margin:0 !important;
}

.truefalse__item-title{
    padding:1.5rem 0 !important;
    margin:0 !important;
}


.truefalse__item-container,.truefalse__label-container{
    border-bottom:2px solid #AEBDE6;
}

.truefalse__item-title_inner{
    font-family: 'FSDillonProRegular' !important;
    // font-size: 1.25rem !important;
    font-size:clamp(1.25rem, 1.25rem + 0vw, 1.25rem) !important;
   // line-height: 1.5rem !important;
   line-height:clamp(1.5rem, 1.5rem + 0vw, 1.5rem) !important;
}

.truefalse__item-radios{
    margin:0 !important;
    padding:0 !important;
}

.truefalse__label-container{
    margin:0 !important;
    padding:0 !important;
}

.truefalse__label{
    margin:0 !important;
    padding:0 !important;
    //font-size: 1.25rem !important;
    font-size:clamp(1.25rem, 1.25rem + 0vw, 1.25rem) !important;
    //line-height: 1.5rem !important;
    line-height:clamp(1.5rem, 1.5rem + 0vw, 1.5rem) !important;
    letter-spacing: 0.004rem !important;
    font-family: 'FSDillonProBold' !important;
}

#wrapper .background-colour1 .truefalse__item-radio.is-selected,
#wrapper .background-colour2 .truefalse__item-radio.is-selected
{
    background-color:transparent !important;
    outline: none !important;
    border: none !important;
}


#wrapper .background-colour1 .truefalse__item-radio.is-selected .element-color-text-icon
{
    color:#041C39 !important;
}

#wrapper .background-colour2 .truefalse__item-radio.is-selected .element-color-text-icon
{
    color:#AEBDE6 !important;
}

#wrapper .truefalse__item-radio:not(.is-selected) .truefalse__item-icon:hover .element-color-text-icon,
#wrapper .truefalse__item-radio:not(.is-selected) .truefalse__item-icon .element-color-text-icon:hover,
#wrapper .truefalse__item-radio:not(.is-selected) .truefalse__item-input:hover + .element-color-text-icon,
#wrapper .page .background-colour1.article .truefalse__item-radio:not(.is-selected) .element-color-text-icon:hover,
#wrapper .page .background-colour2.article .truefalse__item-radio:not(.is-selected) .element-color-text-icon:hover,
{
    color:#355699 !important;
}

.truefalse__item-radio.is-incorrect .truefalse__item-marking-icon .icon:before,
.truefalse__item-radio.is-correct .truefalse__item-marking-icon .icon:before
{
    //content: "\e96e" !important;
    padding: 0 !important;
    margin: 0 !important;
    box-shadow: none !important;
    background-color: #fff !important;
    border: 2px solid;
    height: 1.5rem;
    width: 1.5rem;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1rem;
    font-weight: bold;
    outline: 3px solid #fff;
}

.truefalse__item-radio.is-incorrect .truefalse__item-marking-icon .icon{
    color:#DD221A !important;
}

.truefalse__item-radio.is-correct .truefalse__item-marking-icon .icon{
    color:#039855 !important;
}


.truefalseContainer .component__title *
{
    font-style: normal !important;
    font-family: FSDillonProBold !important;
    font-size:1.669rem !important;
    line-height: 2.25rem !important; 
    letter-spacing: 0.002rem !important;
    background: transparent !important;
    padding: 0 !important;
}

//------------------------------------------------------------------------------
//------------------------------------------------------------------------------

.notify__title-inner{
    color: #041C39 !important;
    //font-size: 1.6rem !important;
    font-size:clamp(1.6rem, 1.6rem + 0vw, 1.6rem) !important;
    font-style: normal;
    font-weight: 700;
    //line-height: 2rem !important;
    line-height:clamp(2rem, 2rem + 0vw, 2rem) !important;
    letter-spacing: 0.002rem !important;
    font-family: 'FSDillonProBold' !important;
    margin:0 !important;
}


.notify__body-inner{
    color: #4F6074 !important;
    display: flex;
    flex-direction: column;
}

.notify__body-inner div,
.notify__body-inner span,
.notify__body-inner ul,
.notify__body-inner li,
.notify__body-inner p{
    font-family: 'FSDillonProRegular' !important;
    color: #4F6074 !important;
    //font-size:1.25rem !important;
    font-size:clamp(1.25rem, 1.25rem + 0vw, 1.25rem) !important;
    //line-height:1.5rem !important;
    line-height:clamp(1.5rem, 1.5rem + 0vw, 1.5rem) !important;
}

.notify__body-inner p,
.notify__body-inner ul
{
    margin:0.5rem 0 !important;
}

.notify__title{
    margin-bottom: 0.75rem;
}

.notify__popup{
    background-color: #e9ebf1 !important;
    display:flex;
    align-items:center;
    justify-content:center;
}

.notify__close-btn .icon:before{
    display:none;
}

#adapt .notify__popup .notify__popup-inner .notify__close-btn {
    background-color: inherit !important;
    border: 2px solid #AEBDE6 !important;
    width: 100%;
    color: #041C39 !important;
    font-family: 'FSDillonProRegular' !important;
    //font-size: 1rem !important;
    font-size:clamp(1rem, 1rem + 0vw, 1rem) !important;
    font-style: normal !important;
    font-weight: 400 !important;
    //line-height: 1.25rem !important;
    line-height:clamp(1.25rem, 1.25rem + 0vw, 1.25rem) !important;
    letter-spacing: 0.02rem !important;
    text-transform:uppercase;
    padding: 12px 64px;
    height: 56px;
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 1;
}

#adapt .notify__popup .notify__popup-inner .notify__close-btn:hover, 
#adapt .notify__popup .notify__popup-inner .notify__close-btn:focus,
{
    color: #041C39 !important;
    border: 2px solid #AEBDE6 !important;
}
    
    
.btn__action.is-full-width, .btn__feedback.is-full-width {
    margin-right: 0;
    border-bottom-left-radius: 4px;
    border-bottom-right-radius: 4px;
}

//--------------------------------------
//----Open text Input-------------------
//--------------------------------------
.opentextinput .opentextinput__inner .opentextinput__widget .opentextinput__count-characters  {
    border-top-left-radius: 4px;
    border-top-right-radius: 4px;
    font-family:'FSDillonProBold' !important;
}

.textinput .component__title,
.textinput .component__title-inner,
.mcqContainer .component__title,
.openTextInput .component__title,
.openTextInput .component__title-inner,
.graphicalMCQ .component__title,
.graphicalMCQ .component__title-inner,
{
    padding:0;
    margin:0;
}

.textinput .component__title-inner,
.textinput .component__title-inner *,
.mcqContainer .component__title-inner,
.mcqContainer .component__title-inner *,
.openTextInput .component__title-inner,
.openTextInput .component__title-inner *
{
//color: #041C39 !important;
font-family: 'FSDillonProBold' !important;
//font-size: 26.7px;
//font-size: 1.669rem !important;
font-size:clamp(1.6688rem, 1.6688rem + 0vw, 1.6688rem) !important;
font-style: normal !important;
font-weight: 700 !important;
//line-height: var(--font-Headline-XS-Line-Height, 36px); /* 134.831% */
//line-height: 2.25rem !important;
line-height:clamp(2.25rem, 2.25rem + 0vw, 2.25rem) !important;
letter-spacing: 0.002rem !important;
}

.openTextInput .js-a11y-completion-description{
    display:none;
}

//.text .component__instruction,
.stackerContainer .component__instruction,
.hiddenHotspots .component__instruction,
.accordion .component__instruction,
.imagegallery .component__instruction,
.referencelist .component__instruction,
.reveal .component__instruction,
.matching .component__instruction,
.branching .component__instruction,
.mcqContainer .component__instruction,
.filInBlanksContainer .component__instruction,
.mediaContainer .component__instruction,
.sliderContainer .component__instruction,
.truefalseContainer .component__instruction,
.flipCardContainer .component__instruction,
.openTextInput .component__instruction,
.textinput .component__instruction,
.graphicalMCQ .component__instruction,
.hotGraphicContainer .component__instruction
{
    padding: 0;
    margin: 0;
}

.text .component__instruction-inner,
.stackerContainer .component__instruction-inner,
.hiddenHotspots .component__instruction-inner,
.accordion .component__instruction-inner,
.imagegallery .component__instruction-inner,
.referencelist .component__instruction-inner,
.reveal .component__instruction-inner,
.matching .component__instruction-inner,
.branching .component__instruction-inner,
.mcqContainer .component__instruction-inner,
.filInBlanksContainer  .component__instruction-inner,
.graphicContainer .component__instruction-inner,
.sliderContainer .component__instruction-inner,
.truefalseContainer .component__instruction-inner,
.flipCardContainer .component__instruction-inner,
.openTextInput .component__instruction-inner,
.textinput .component__instruction-inner,
.graphicalMCQ .component__instruction-inner,
.hotGraphicContainer .component__instruction-inner
{
    padding-top: 0.75rem;
    color: #4F6074;
    font-family: 'FSDillonProRegular' !important;
    //font-size: 1rem;
    font-size:clamp(1rem, 1rem + 0vw, 1rem);
    font-style: normal;
    font-weight: 400;
    //line-height: 1.25rem; /* 125% */
    line-height:clamp(1.25rem, 1.25rem + 0vw, 1.25rem);
    letter-spacing: 0.02rem;
}


.openTextInput .component__instruction-inner:after,
.graphicalMCQ .component__instruction-inner:after,
{
    border-top: 1px solid;
    border-color: #CED1DA;
    content: '';
    display: block;
    left: 0;
    position: absolute;
    top: 0;
    width: 100%;
}

.openTextInput .opentextinput__count-characters{
    padding: 1.5rem 0 1rem 0 !important;
    //font-size: 1rem !important;
    font-size:clamp(1rem, 1rem + 0vw, 1rem) !important;
    //line-height: 1.25rem !important;
    line-height:clamp(1.25rem, 1.25rem + 0vw, 1.25rem) !important;
    letter-spacing: 0.015px !important;
}

.textinput .opentextinput__item-textbox,
.openTextInput .opentextinput__item-textbox{
    min-height: 17.37rem !important;
    border: 2px solid #AEBDE6 !important;
    padding: 0.75rem 1rem !important;
    border-radius:4px;
}

.textinput .opentextinput__item-textbox:focus-within,
.textinput .opentextinput__item-textbox:focus-visible,
.textinput .opentextinput__item-textbox:focus,
.openTextInput .opentextinput__item-textbox:focus-within,
.openTextInput .opentextinput__item-textbox:focus-visible,
.openTextInput .opentextinput__item-textbox:focus
{
 border: 2px solid #041C39 !important;
}

.openTextInput .opentextinput__item-textbox, 
.openTextInput .opentextinput__item-textbox *{
    //font-size: 1.25rem !important;
    font-size:clamp(1.25rem, 1.25rem + 0vw, 1.25rem) !important;
    //line-height: 1.5rem !important;
    line-height:clamp(1.5rem, 1.5rem + 0vw, 1.5rem) !important;
    font-family: 'FSDillonProRegular' !important;
    color:#4F6074 !important;
}

.openTextInput .btn__container{
    margin-top:1.5rem !important;
}


//---------------------------------------
.btn__response-container .btn__action:not(.is-full-width), .btn__response-container .btn__feedback:not(.is-full-width) {
    width: 49.5%;
    border-radius: 4px;
}

body .notify__close-btn {
    color: #011e41;
    background-color: #fff;
    display: inline-block;
    float: none;
    margin-top: 1.875rem;
    opacity: .7;
    padding: 1.875rem 1.875rem 1.875rem 1.875rem;
    text-decoration: none;
    transition: all .3s;
    width: auto;
    border-radius: 4px;
}

// ---------------------------------------------------------
// Rounded corners to Narrative images
// ---------------------------------------------------------

.hotgraphic-popup__item-image {
    border-radius: 4px;
}


// ---------------------------------------------------------
// Removes red stroke from narrative progress buttons
// ---------------------------------------------------------

.narrative .narrative__inner .narrative__progress {
    background-color: rgba(255,255,255,0.5);
    border: 0rem solid #e1261c;
}

// ---------------------------------------------------------
// Hover on mouse over
// ---------------------------------------------------------

.growhover:hover {
transition: transform .2s;
  transform: scale(1.1);
}

.unhover {
transition: transform .2s;
}

// ---------------------------------------------------------
// Animated Gradient Background
// ---------------------------------------------------------

.location-menu.cinnamonmenu .cinnamon-wrapper {
background: linear-gradient(-45deg, #214C99, #011E41, #004AA3, #214C99);
    background-size: 400% 400%;
    animation: gradient 15s ease infinite;
@keyframes gradient {
    0% {
        background-position: 0% 50%;
    }
    50% {
        background-position: 100% 50%;
    }
    100% {
        background-position: 0% 50%;
    }
}
}

.location-menu.cinnamonmenu .nav {
    background-color: rgba(255, 0, 0, 0);
    color: #fff;
    margin: 0;
    padding-bottom: 0;
}

#wrapper.cinnamonmenu .menu-item__inner {
    background-color: rgba(255, 0, 0, 0);
    color: #fff;
    margin: 0;
    padding-bottom: 0;
}

// ---------------------------------------------------------
// Removes red stroke from Narrative popup
// ---------------------------------------------------------

.notify.hotgraphic .notify__popup .notify__content .hotgraphic-popup__inner {
    border: 0rem solid #e1261c;}
    
    
// ---------------------------------------------------------
// Fonts
// ---------------------------------------------------------

@font-face {
  font-family: FSDillonProBold;
  font-style: normal;
  src: url('https://cdn.thefa.com/thefawebsite/dist/FSDillonProBold.woff');
}

@font-face {
  font-family: FSDillonProBoldIt;
  font-style: italic;
  src: url('https://cdn.thefa.com/thefawebsite/dist/FSDillonProBoldIt.woff');
}

@font-face {
  font-family: FSDillonProMedium;
  font-style: normal;
  src: url('https://cdn.thefa.com/thefawebsite/dist/FSDillonProMedium.woff');
}

@font-face {
  font-family: FSDillonProMediumIt;
  font-style: italic;
  src: url('https://cdn.thefa.com/thefawebsite/dist/FSDillonProMediumIt.woff');
}

@font-face {
  font-family: FSDillonProRegular;
  font-style: normal;
  src: url('https://cdn.thefa.com/thefawebsite/dist/FSDillonProRegular.woff');
}

@font-face {
  font-family: FSDillonProItalic;
  font-style: italic;
  src: url('https://cdn.thefa.com/thefawebsite/dist/FSDillonProItalic.woff');
}

// ---------------------------------------------------------
// Custom Header text
// ---------------------------------------------------------

//remove later
.HeaderText {
    font-family: FSDillonProBold;
    font-style: normal;
    color: white;
    float: center;
    clear: both;
    display: inline-block;
    //line-height: 100%;
    line-height:4rem;
    //font-size: clamp(15px, 5vw,5vw);
    //font-size:4rem;
   // font-size: clamp(2.3313rem, 1.7682rem + 2.8152vw, 3.95rem);
}

.Hero-text{
    font-family: 'FSDillonProBold';
    font-style: normal;
    color: white;
    float: center;
    clear: both;
    display: inline-block;
    //line-height:4rem;
    line-height:clamp(4rem, 4rem + 0vw, 4rem);
}
// ---------------------------------------------------------
// Type styles
// ---------------------------------------------------------

.H1 {
    font-family: FSDillonProBold !important;
    font-style: normal;
    line-height: 84px;
    font-size: 84.17px;
}

.H2 {
    font-family: FSDillonProBold !important;
    font-style: normal;
    line-height: 68px;
    font-size: 63.15px;
}

.H3 {
    font-family: FSDillonProBold !important;
    font-style: normal;
    line-height: 52px;
    //font-size: 47.37px;
    font-size:clamp(2.3328rem, 2.0827rem + 1.2504vw, 3.0518rem);
}

.H4 {
    font-family: FSDillonProBold !important;
    font-style: normal;
    //float: left;
    //clear: both;
    //display: inline-block;
    line-height: 40px;
    font-size: 35.54px;
}

.H5_old {
    font-family: FSDillonProBold !important;
    font-style: normal;
    line-height: 36px;
    //font-size: 26.6px;
    //font-size: clamp(1.62rem, 1.5041rem + 0.5793vw, 1.9531rem);
    font-size: 1.666rem;
    //font-size: clamp(1.125rem, 1.052rem + 0.3652vw, 1.335rem);
    //color:#041C39;
}

.H5 {
    font-family: FSDillonProBold !important;
    font-style: normal !important;
    font-size: 2.221rem !important;
    // font-size: 2.22rem !important;
    font-size:clamp(2.22rem, 2.22rem + 0vw, 2.22rem) !important;
    //line-height: 2.5rem !important;
    line-height:clamp(2.5rem, 2.5rem + 0vw, 2.5rem) !important;
    letter-spacing: 0.004rem !important;
}


.H6 {
    font-family: 'FSDillonProBold' !important;
    font-style: normal !important;
    font-size: 1.66rem !important;
    line-height: 2.25rem !important; 
    letter-spacing: 0.002rem !important;
}

.subHeadline {
    font-family: FSDillonProBold !important;
    font-style: normal;
    line-height: 36px;
    //font-size: 26.6px;
    //font-size: clamp(1.62rem, 1.5041rem + 0.5793vw, 1.9531rem);
    //font-size: 1.666rem;
    //font-size: clamp(1.125rem, 1.052rem + 0.3652vw, 1.335rem);
    //color:#041C39;
}

//remove later
.subText {
    //color: var(--text-general-body-dark-text, #4F6074);
    font-family: 'FSDillonProRegular' !important;
    //font-size: 16px;
    //font-size: 1.25rem;
    font-size:clamp(1.25rem, 1.25rem + 0vw, 1.25rem);
    font-style: normal;
    font-weight: 400;
    //line-height: var(--spacing-spacing-scale-5, 20px);
    //line-height:1.5rem;
    line-height:clamp(1.5rem, 1.5rem, 1.5rem) !important;
    //letter-spacing: 0.32px;
    letter-spacing: 0.02rem;
}

.Headline {
    font-family: FSDillonProBold !important;
    //font-size:2.219rem !important;
    font-size:clamp(2.219rem, 2.219rem + 0vw, 2.219rem) !important;
    //line-height: 2.5rem !important;
    line-height:clamp(2.5rem, 2.5rem + 0vw, 2.5rem);
    letter-spacing: 0.004rem !important;
}

.Sub-Headline {
    font-family: FSDillonProBold !important;
   //font-size:1.669rem !important;
    font-size:clamp(1.669rem, 1.669rem + 0vw, 1.669rem) !important;
    //line-height: 2.25rem !important; 
    line-height:clamp(2.25rem, 2.25rem + 0vw, 2.25rem) !important;
    letter-spacing: 0.002rem !important;
}

.Body-Regular,
.text__body-inner,
.text__body-inner p,
.text__body-inner ul,
.text__body-inner li,
.narrative__content-body-inner p,
.narrative__content-body-inner ul,
.narrative__content-body-inner li
{
    font-family: 'FSDillonProRegular' !important;
    //font-size: 1.25rem;
    //font-size: clamp(1.125rem, 1.225rem, 1.25rem);
    font-size: clamp(1.25rem, 1.25rem, 1.25rem) !important;
    font-style: normal;
    font-weight: 400;
    //line-height:1.5rem;
    line-height: clamp(1.5rem, 1.5rem, 1.5rem);
    letter-spacing: 0.02rem;
}

.Body-Bold,.Question {
    font-family: 'FSDillonProBold' !important;
    //font-size: 1.25rem;
    font-size: clamp(1.25rem, 1.25rem + 0vw, 1.25rem);
    //font-size: clamp(1.125rem, 1.225rem, 1.25rem);
    font-style: normal;
    font-weight: 400;
    line-height:1.5rem;
    letter-spacing: 0.02rem;
}

.Body-Link{
    font-family: 'FSDillonProRegular' !important;
    //font-size: 1rem;
    font-size: clamp(1rem, 1rem + 0vw, 1rem) !important;
    font-style: normal;
    font-weight: 400;
    line-height: 1.25rem;
    letter-spacing: 0.02rem;
    text-decoration-line: underline;
    text-decoration-style: solid;
    text-decoration-skip-ink: none;
    text-decoration-thickness: auto;
    text-underline-offset: auto;
    text-underline-position: from-font;
}

.Body-Link-Regular{
    font-family: 'FSDillonProRegular' !important;
    //font-size: 1.25rem;
    font-size: clamp(1.25rem, 1.25rem + 0vw, 1.25rem) !important;
    //font-size: clamp(1.125rem, 1.225rem, 1.25rem);
    font-style: normal;
    font-weight: 400;
    line-height:1.5rem;
    letter-spacing: 0.02rem;
    text-decoration-line: underline;
    text-decoration-style: solid;
    text-decoration-skip-ink: none;
    text-decoration-thickness: auto;
    text-underline-offset: auto;
    text-underline-position: from-font;
}

.background-colour1 .Body-Link,
.background-colour1 .Body-Link:hover,
.background-colour1 .Body-Link:focus,
.background-colour1 .Body-Link:visited,
.background-colour1 .Body-Link-Regular,
.background-colour1 .Body-Link-Regular:hover,
.background-colour1 .Body-Link-Regular:focus,
.background-colour1 .Body-Link-Regular:visited,
#adapt #app #wrapper .background-colour1 .component__inner .customlink,
#adapt #app #wrapper .background-colour1 .component__inner .customlink:hover,
#adapt #app #wrapper .background-colour1 .component__inner .customlink:focus,
#adapt #app #wrapper .background-colour1 .component__inner .customlink:visited
{
    color:#024597 !important;
}


.background-colour2 .Body-Link,
.background-colour2 .Body-Link:hover,
.background-colour2 .Body-Link:focus,
.background-colour2 .Body-Link:visited,
.background-colour2 .Body-Link-Regular,
.background-colour2 .Body-Link-Regular:hover,
.background-colour2 .Body-Link-Regular:focus,
.background-colour2 .Body-Link-Regular:visited,
#adapt #app #wrapper .background-colour2 .component__inner .customlink,
#adapt #app #wrapper .background-colour2 .component__inner .customlink:hover,
#adapt #app #wrapper .background-colour2 .component__inner .customlink:focus,
#adapt #app #wrapper .background-colour2 .component__inner .customlink:visited
{
    //color:#F0F1F4 !important;
    color:#AEBDE6 !important;
}

//remove later
.background-colour1 .element-color-static .subText{
    color:#4F6074;
}

.background-colour1 .Body-Regular
{
    //color:#4F6074;
    color:#424a5c;
}

.background-colour1 .Body-Bold,
.background-colour1 .Question {
    color:#041C39;
}

//remove later
.background-colour2 .element-color-static .subText{
    color:#E9EBF1;
}

.background-colour2 .Body-Regular,
.background-colour2 .Body-Bold,
.background-colour2 .Question,
{
    color:#E9EBF1;
}

.p {
    font-family: FSDillonProRegular;
    font-style: normal;
    float: left;
    clear: both;
    display: inline-block;
    line-height: 24px;
    //font-size: 20px;
    font-size: clamp(1.125rem, 1.1rem + 0.125vw, 1.25rem);
    //color:#4F6074;
}

.plable {
    font-family: FSDillonProRegular;
    font-style: normal;
    color: #4F6074;
    float: left;
    clear: both;
    display: inline-block;
    //line-height: 20px;
    line-height:clamp(1.25rem, 1.25rem + 0vw, 1.25rem);
    //font-size: 15px;
    font-size:clamp(0.9375rem, 0.9375rem + 0vw, 0.9375rem);
    letter-spacing: 1.2px;
    border-bottom: 1px solid #DD221A;
    padding-bottom: 1px;
    text-decoration: none;
    display: block;
    margin-bottom: 10px;
}

.mandatory{
    font-family: FSDillonProRegular !important;
    font-style: normal;
    //color: #fff !important;
    color: #041C39 !important;
    font-weight: 700;
    line-height: 20px;
    //font-size: 0.875rem;
    font-size: clamp(0.8888rem, 0.8888rem + 0vw, 0.8888rem);
    letter-spacing: 1.2px;
    text-decoration: none;
    margin-bottom: 10px;
    padding: 4px 8px;
    //background-color: #1E438E;
    background-color: #D2D9E8;
    border-radius:4px;
    width: auto !important;
    display: flex;
    align-items: center;
    gap: 4px;
    display: flex;
    margin-bottom: 0;
    margin-top: 0;
    width: max-content !important;
}
//.mandatory:before{
//    content: "\e908" !important;
//    font-size:1rem;
//}


// ---------------------------------------------------------
// Custom Header padding
// ---------------------------------------------------------

//remove later
.HeaderPadding {
    padding-bottom: 50px;
    padding-top: 50px;
}

.Module-Hero .block,
.Topic-Hero .block{
    padding-bottom: 50px;
    padding-top: 50px;
}

// ---------------------------------------------------------
// Mentor Font Size adjustment
// ---------------------------------------------------------
.mentor {
    left: 0;
    text-align: center;
    font-size: 1.3rem;
    line-height: 1.3em;
    height: auto;
}
// ---------------------------------------------------------
// Blocks
// ---------------------------------------------------------

.block {
    &.remove-block-padding-bottom {
        .block__inner {
            padding-bottom: 0px;
        }
    }
    
    &__title-inner {
        text-transform: uppercase;
        
        &.element-color-static {
            background-color: rgba(0,0,0,0) !important;
            background-color: transparent !important;
        }
    }
    
    &__body-inner.element-color-static {
        background-color: rgba(0,0,0,0) !important;
        background-color: transparent !important;
    }
}

.reduce-spacing-block-title-body {
    .block {
        &__title-inner {
            padding-bottom: 0;
        }
        
        &__body-inner {
            padding-top: 0;
        }
    }
}

body .block__inner {
    padding-bottom: 1rem;
}
// ---------------------------------------------------------
// Chapter text
// ---------------------------------------------------------


.chapter {
  color: white; /* White text */
  padding: 5px 20px; /* Vertical and horizontal padding */
  border-radius: 25px; /* Rounded corners */
  font-family: FSDillonProRegular; /* Sans-serif font */
  //font-size: 15px; /* Adjust as needed */
  font-size: clamp(0.9375rem, 0.9375rem + 0vw, 0.9375rem);
  font-weight: bold; /* Bold text */
  text-transform: uppercase; /* All caps */
  letter-spacing: 1.2px;
  display: inline-block; /* To make the background fit the content */
  border: 2px solid #AEBDE6; /* Light grey border */
}

// ---------------------------------------------------------
// mcq styling
// ---------------------------------------------------------

.mcq__widget {
    display: flex;
    flex-direction: column;
    gap: 16px;
    margin-top: 24px;
}

.mcqContainer .component__inner{
    display: flex;
    flex-direction: column;
}

.truefalse__item-radio-true{
    border-right:none !important;
}

.truefalse__item-radio-false{
    border-left:none !important;
}


.hiddenHotspots .block__inner,
.matchingQuestion .block__inner,
.assesmentResults .block__inner,
.filInBlanksContainer .block__inner,
.stackerContainer .block__inner,
.sliderContainer .block__inner,
.truefalseContainer .block__inner,
.flipCardContainer .block__inner,
.mcqContainer .block__inner, 
.mediaContainer .block__inner,
.openTextInput .block__inner,
.textinputContainer .block__inner,
.graphicalMCQ .block__inner
{
    display:flex;
    flex-direction:column;
    padding: 3rem 3.5rem;
    border-radius: 4px;
}

.mediaContainer .block__inner{
    padding: 0 !important;
}

.mediaContainer .js-skip-to-transcript{
    display:none !important;
}

//.mcqContainer .block__body-inner{
.block__body-inner{
    padding:0;
}

//.mcq .btn__marking,
//.gmcq .btn__marking,
.hiddenHotspots .btn__marking,
.textinput .btn__marking,
.matching .btn__marking,
.filInBlanksContainer .btn__marking,
.stackerContainer .btn__marking,
.slider .btn__marking,
.confidenceslider .btn__marking,
.truefalse .btn__marking
{
   // display:none;
}

.background-colour1 .hiddenHotspots .block__inner,
.background-colour1 .textinputContainer .block__inner,
.background-colour1 .matchingQuestion .block__inner,
.background-colour1 .assesmentResults .block__inner,
.background-colour1 .filInBlanksContainer .block__inner,
.background-colour1 .stackerContainer .block__inner,
.background-colour1 .sliderContainer .block__inner,
.background-colour1 .truefalseContainer .block__inner,
.background-colour1 .flipCardContainer .block__inner,
.background-colour1 .mcqContainer .block__inner,
.background-colour1 .openTextInput .block__inner,
.background-colour1 .graphicalMCQ .block__inner
{
    background-color: #ffffff;
    border: 1px solid #CED1DA;
}

.background-colour2 .hiddenHotspots .block__inner,
.background-colour2 .textinputContainer .block__inner,
.background-colour2 .matchingQuestion .block__inner,
.background-colour2 .assesmentResults .block__inner,
.background-colour2 .filInBlanksContainer .block__inner,
.background-colour2 .stackerContainer .block__inner,
.background-colour2 .sliderContainer .block__inner,
.background-colour2 .truefalseContainer .block__inner,
.background-colour2 .flipCardContainer .block__inner,
.background-colour2 .mcqContainer .block__inner,
.background-colour2 .openTextInput .block__inner,
.background-colour2 .graphicalMCQ .block__inner
{
   //background-color: #323231;
   background-color: #404040;
   border: 1px solid #5F5F5F;
}

.textinput .btn__response-container,
.matching .btn__response-container {
    flex-direction:column;
}

.hiddenHotspots .btn__response-container,
.stackerContainer .btn__response-container,
.sliderContainer .btn__response-container,
.truefalseContainer .btn__response-container,
.mcqContainer .btn__response-container {
    flex-direction:column;
    margin-top: 16px;
}

.hiddenHotspots .btn__response-container .btn-text,
.textinput .btn__response-container .btn-text,
.matching .btn__response-container .btn-text,
.stackerContainer .btn__response-container .btn-text,
.sliderContainer .btn__response-container .btn-text,
.truefalseContainer .btn__response-container .btn-text,
.mcqContainer .btn__response-container .btn-text,
.graphicalMCQ .btn__response-container .btn-text
{
    width: 100% !important;
    margin: 8px 0 !important;
    //font-size: 1.125rem !important;
    font-size:clamp(1.125rem, 1.125rem + 0vw, 1.125rem) !important;
}

//MCQ
.mcq .mcq__inner .mcq__widget .mcq-item__state.mcq-item__state-correctness{
    //display:none !important;
}

//GMCQ
.gmcq .gmcq__inner .gmcq__widget .gmcq-item__state.gmcq-item__state-correctness{
    //display:none !important;
}

//MCQ
.mcq-item__text,
{
    display: block;
    //border-radius: 4px;
    //border: 2px solid #AEBDE6;
    width:100%;
}


//MCQ
.mcq-item__label
{
    border-radius: 4px !important;
    border: 2px solid #AEBDE6 !important;
}

//GMCQ
.gmcq-item__option{
    border-radius: var(--spacing-spacing-scale-1, 4px);
    border: 2px solid var(--border-primary--button-border-input-field, #AEBDE6);
}

.background-colour2 .gmcq-item__option{
     background-color: rgba(255, 255, 255, 0.10);
}

.mcq-item__text-inner,
.gmcq-item__text-inner
{
    font-family: FSDillonProRegular;
    display: block;
    letter-spacing: 0px;
    margin-bottom: 0px;
    //padding: 0px 0px 0px 2.8125rem;
    position: relative;
    z-index: 2;
    //font-size: 20px;
    font-size: clamp(1.125rem, 1.1rem + 0.125vw, 1.25rem) !important;
    //line-height: 1.875rem;
    line-height:24px;
}


//MCQ
.background-colour2 .mcqContainer .mcq-item__label:hover .mcq-item__text-inner,
.background-colour2 .mcqContainer .mcq-item__label.is-selected .mcq-item__text-inner,
.background-colour1 .mcqContainer .mcq-item__text-inner{
    color:#041C39;
}

//GMCQ
.background-colour2 .graphicalMCQ .gmcq-item__option:hover .gmcq-item__text-inner,
.background-colour2 .graphicalMCQ .gmcq-item__label.is-selected .gmcq-item__text-inner,
.background-colour1 .graphicalMCQ .gmcq-item__text-inner{
    color:#041C39;
}

//MCQ
.background-colour2 .mcqContainer .mcq-item__text-inner{
    color:#FFFFFF;
}

//GMCQ
.background-colour2 .graphicalMCQ .gmcq-item__text-inner{
    color:#FFFFFF;
}

//MCQ
#wrapper .mcq label.is-selected {
    background-color: #E9EBF1;
    color: #E9EBF1;
}

//GMCQ
#wrapper .gmcq label.is-selected {
    background-color: #E9EBF1;
    color: #E9EBF1;
}

//MCQ
#wrapper .mcq label.is-selected:before, #wrapper .mcq label.is-selected:after {
    visibility: hidden;
}

//GMCQ
#wrapper .gmcq label.is-selected:before, #wrapper .gmcq label.is-selected:after {
    visibility: hidden;
}

//MCQ
#wrapper .mcq .mcq-item__label:hover {
    background-color:#F3F3F3 !important;
}

//GMCQ
#wrapper .gmcq .gmcq-item__option:hover{
    background-color:#F3F3F3 !important;
}

//MCQ
#wrapper .mcq .mcq-item__label:hover .mcq-item__icon .icon{
    color:#355699 !important;
}

//GMCQ
#wrapper .gmcq .gmcq-item__label:hover .gmcq-item__icon .icon{
    color:#355699 !important;
}

//MCQ
#wrapper .background-colour2 .mcq-item__label .mcq-item__icon .icon{
    color:#AEBDE6 !important;
}

//GMCQ
#wrapper .background-colour2 .gmcq-item__label .gmcq-item__icon .icon{
    color:#AEBDE6 !important;
}

//MCQ
#wrapper .mcq .mcq-item__label:hover .mcq-item__text {
    //border-color:#1E438E;
}

//MCQ
#wrapper .mcq .mcq-item__label:hover {
    border-color:#1E438E;
}

//GMCQ
#wrapper .gmcq .gmcq-item__label:hover .gmcq-item__text {
    border-color:#1E438E;
}

//MCQ
#wrapper .mcq .is-selected{
    background-color:#E9EBF1 !important;
}

//GMCQ
#wrapper .gmcq .is-selected .gmcq-item__option{
    background-color:#E9EBF1 !important;
}

//MCQ
#wrapper .mcq .is-selected .mcq-item__text{
    border-color:#355699 !important;
}

//MCQ
#wrapper .mcq .is-selected .mcq-item__label{
    //border-color:#355699 !important;
}

#wrapper .mcq .is-selected{
    border-color:#355699 !important;
}

//GMCQ
#wrapper .gmcq .is-selected .gmcq-item__text{
    border-color:#355699 !important;
}

//MCQ
#wrapper .mcq .is-selected .mcq-item__icon .icon{
    color: #1E438E !important;
}

//GMCQ
#wrapper .gmcq .is-selected .gmcq-item__icon .icon{
    color: #1E438E !important;
}

//MCQ
#wrapper .mcq .is-incorrect .is-selected{
    background-color:#FBE1DF !important;
}

//GMCQ
#wrapper .gmcq .is-incorrect .is-selected .gmcq-item__option{
    background-color:#FBE1DF !important;
}

//MCQ
#wrapper .mcq .is-correct .is-selected{
    background-color:#ECFDF3 !important;
}

//GMCQ
#wrapper .gmcq .is-correct .is-selected .gmcq-item__option{
    background-color:#ECFDF3 !important;
}

//MCQ
//modification for radio button
#wrapper .mcq .mcq-item__state:has(.is-radio) .mcq-item__correct-icon .icon:before,
#wrapper .mcq .mcq-item__state:has(.is-radio) .mcq-item__incorrect-icon .icon:before
{
    content: "\e96e" !important; 
}

//GMCQ
//modification for radio button
#wrapper .gmcq .gmcq-item__state:has(.is-radio) .gmcq-item__correct-icon .icon:before,
#wrapper .gmcq .gmcq-item__state:has(.is-radio) .gmcq-item__incorrect-icon .icon:before
{
    content: "\e96e" !important; 
}

//MCQ
//modification for check box
#wrapper .mcq .mcq-item__state:has(.is-checkbox) .mcq-item__correct-icon .icon:before,
#wrapper .mcq .mcq-item__state:has(.is-checkbox) .mcq-item__incorrect-icon .icon:before
{
    content: "\e974" !important; 
}

//GMCQ
//modification for check box
#wrapper .gmcq .gmcq-item__state:has(.is-checkbox) .gmcq-item__correct-icon .icon:before,
#wrapper .gmcq .gmcq-item__state:has(.is-checkbox) .gmcq-item__incorrect-icon .icon:before
{
    content: "\e974" !important; 
}

//MCQ
#wrapper .mcq .is-incorrect .is-selected .mcq-item__icon .icon{
    color: #DD221A !important;
}

//GMCQ
#wrapper .gmcq .is-incorrect .is-selected .gmcq-item__icon .icon{
    color: #DD221A !important;
}

//MCQ
#wrapper .mcq .mcq__inner .mcq__widget .is-incorrect .is-selected .mcq-item__text{
   // border-color:#EE908C !important;
}

#wrapper .mcq .mcq__inner .mcq__widget .is-incorrect .is-selected{
   border-color:#EE908C !important;
}

//GMCQ
#wrapper .gmcq .gmcq__inner .gmcq__widget .is-incorrect .is-selected .gmcq-item__option{
    border-color:#EE908C !important;
}

//MCQ
#wrapper .mcq .mcq__inner .mcq__widget .is-correct .is-selected .mcq-item__text{
    //border-color:#D1FADF !important;
}

#wrapper .mcq .mcq__inner .mcq__widget .is-correct .is-selected{
    border-color:#D1FADF !important;
}

//GMCQ
#wrapper .gmcq .gmcq__inner .gmcq__widget .is-correct .is-selected .gmcq-item__option{
    border-color:#D1FADF !important;
}

//MCQ
#wrapper .mcq .is-incorrect .mcq-item__icon .icon{
    color: #DD221A !important;
}

//GMCQ
#wrapper .gmcq .is-incorrect .gmcq-item__icon .icon{
    color: #DD221A !important;
}

//MCQ
#wrapper .mcq .mcq__inner .mcq__widget .mcq-item label .mcq-item__icon.mcq-item__correct-icon .icon {
    color: #039855 !important;
}

//GMCQ
#wrapper .gmcq .gmcq__inner .gmcq__widget .gmcq-item label .gmcq-item__icon.gmcq-item__correct-icon .icon {
    color: #039855 !important;
}

//MCQ
#wrapper .mcq .mcq__inner .mcq__widget .mcq-item label .mcq-item__icon.mcq-item__correct-icon .icon:before, #wrapper .mcq .mcq__inner .mcq__widget .mcq-item label .mcq-item__icon.mcq-item__incorrect-icon .icon:before {
    border-radius: 50%;
    position: absolute;
    top: .8rem;
    background-color: transparent !important;
    box-shadow: none !important;
}

//MCQ
#wrapper .mcq .mcq__inner .mcq__widget .mcq-item label .mcq-item__state-correctness .mcq-item__icon.mcq-item__icon .icon {
    position:relative;
}

//MCQ
#wrapper .mcq .mcq__inner .mcq__widget .mcq-item label .mcq-item__state-correctness .mcq-item__icon.mcq-item__correct-icon .icon:before, 
#wrapper .mcq .mcq__inner .mcq__widget .mcq-item label .mcq-item__state-correctness .mcq-item__icon.mcq-item__incorrect-icon .icon:before{
    left: -1.5rem;
    font-size: 1rem;
    font-weight:bold;
    width:2.3rem;
    height:2.3rem;
    display: flex;
    align-items:center;
    justify-content:center;
}

//MCQ
#wrapper .mcq .mcq__inner .mcq__widget .mcq-item label .mcq-item__state-correctness .mcq-item__icon.mcq-item__incorrect-icon .icon:before{
    color: #DD221A !important;
    background: #fff !important;
    border: 3px solid #DD221A !important;
}

//GMCQ
#wrapper .page .article .block .gmcq__inner .gmcq__widget .gmcq-item label .gmcq-item__state-correctness .gmcq-item__icon.gmcq-item__incorrect-icon .icon{
    color: #DD221A !important;
    background: #fff !important;
    border: 3px solid #DD221A !important;
}

//MCQ
#wrapper .mcq .mcq__inner .mcq__widget .mcq-item label .mcq-item__state-correctness .mcq-item__icon.mcq-item__correct-icon .icon:before{
    color: #039855 !important;
    background: #fff !important;
    border: 3px solid #039855 !important;
}

//GMCQ
#wrapper .page .article .block .gmcq__inner .gmcq__widget .gmcq-item label .gmcq-item__state-correctness .gmcq-item__icon.gmcq-item__correct-icon .icon{
    color: #039855 !important;
    background: #fff !important;
    border: 3px solid #039855 !important;
}

//GMCQ
#wrapper .gmcq .gmcq__inner .gmcq__widget .gmcq-item label .gmcq-item__state-correctness .gmcq-item__icon.gmcq-item__correct-icon .icon:before, 
#wrapper .gmcq .gmcq__inner .gmcq__widget .gmcq-item label .gmcq-item__state-correctness .gmcq-item__icon.gmcq-item__incorrect-icon .icon:before
{
    font-size: 1rem;
    font-weight:bold;
}

.btn__marking,
.mcq .btn__marking,
.gmcq .btn__marking{
    top: 0;
}

.btn__marking.is-incorrect .icon,
.mcq .btn__marking.is-incorrect .icon,
.gmcq .btn__marking.is-incorrect .icon
{
    background-color:#DD221A;
}

.btn__marking.is-correct .icon,
.mcq .btn__marking.is-correct .icon,
.gmcq .btn__marking.is-correct .icon
{
    background-color:#039855;
}

.btn__marking .icon:before,
.mcq .btn__marking .icon:before,
.gmcq .btn__marking .icon:before
{
    //font-size: 1.25rem;
    font-size: 1rem;
    font-weight: bold;
}

//GMCQ
#wrapper .gmcq .gmcq__inner .gmcq__widget .gmcq-item label .gmcq-item__icon.gmcq-item__correct-icon .icon:before, 
#wrapper .gmcq .gmcq__inner .gmcq__widget .gmcq-item label .gmcq-item__icon.gmcq-item__incorrect-icon .icon:before,
#wrapper .gmcq .gmcq__inner .gmcq__widget .gmcq-item label .gmcq-item__icon.gmcq-item__answer-icon .icon:before
{
    font-size: 1.25rem;
}

#wrapper .gmcq .gmcq__inner .gmcq__widget .gmcq-item label .gmcq-item__icon.gmcq-item__correct-icon .icon, 
#wrapper .gmcq .gmcq__inner .gmcq__widget .gmcq-item label .gmcq-item__icon.gmcq-item__incorrect-icon .icon,
#wrapper .gmcq .gmcq__inner .gmcq__widget .gmcq-item label .gmcq-item__icon.gmcq-item__answer-icon .icon
{
    border-radius: 50%;
    //position: absolute;
    //top: .8rem;
    background-color: transparent !important;
    box-shadow: none !important;
    
    display:flex;
    align-items:center;
    justify-content:center;
    position: unset !important;
}    


//MCQ
#wrapper .mcq-item__answer-icon .icon:before{
    width:2.3rem !important;
}

//GMCQ
#wrapper .gmcq-item__answer-icon .icon:before{
   // width:2.3rem !important;
}

.gmcq-item__option{
    position:relative;
    
    display: flex;
    flex-direction: column;
    flex-direction: row;
    align-items: center;
}

.gmcq__inner .gmcq__widget .gmcq-item__state {
   // left: 0 !important;
   // top: 0.35rem !important;
    position: relative !important;
    left: 0 !important;
    top: 0 !important;
    display: flex !important;
    align-items: center !important;
    justify-content: center !important;
}

.gmcq__inner .gmcq__widget .gmcq-item__state.gmcq-item__state-correctness{
    position: absolute !important;
    left: unset !important;
    right: 0 !important;
}

.gmcq__inner .gmcq__widget .gmcq-item__text-inner{
    padding:0 !important;
}

#wrapper .mcq-item__label{
display: flex;
align-items: center;
border-radius: var(--spacing-spacing-scale-1, 4px);
}

.gmcq__widget{
    margin-left: -0.5rem;
    margin-right: -0.5rem;
    margin-top: 1.125rem;
    margin-bottom: 0.75rem;
}

.gmcq__widget .gmcq-item{
    padding:0.5rem;
}

.gmcq-item__option{
    margin-top:1rem;
}

.graphicalMCQ .component__title-inner,
.graphicalMCQ .component__title-inner *{
    font-family: FSDillonProBold !important;
    font-style: normal !important;
    font-size: 2.221rem !important;
    font-size: 2.22rem !important;
    line-height: 2.5rem !important;
    letter-spacing: .004rem !important;
    background: transparent !important;
    padding: 0 !important;
}

//remove padding from top row
//.gmcq__widget > .gmcq-item:nth-child(-n+var(--columns)) {
//    padding-top:0;
//}

//remove padding from bottom row
//.gmcq__widget > .gmcq-item:nth-child(-n+var(--columns)) {
//    padding-bottom:0;
//}

//remove padding from extreme left
//.gmcq__widget:not(.has-column-layout) > .gmcq-item:nth-child(2n+1) {
//    padding-left:0;
//}

//remove padding from extreme right
//.gmcq__widget:not(.has-column-layout) > .gmcq-item:nth-child(2n) {
//    padding-right:0;
//}

//.gmcq__widge.has-column-layout > .gmcq-item:nth-child(4n+1) {
//    padding-left:0;
//}

//.gmcq__widget.has-column-layout > .gmcq-item:nth-child(4n) {
//    padding-right:0;
//}

// media styling
// ---------------------------------------------------------

.mediaContainer .component__instruction,
.mediaContainer .component__instruction-inner{
    padding:0;
}

.mediaContainer .component__inner{
    display: flex;
    //flex-direction: column-reverse;
    flex-direction: column;
    //margin-top: 8px;
}

.mediaContainer .component__widget{
    margin-top: 12px;
}

.mediaContainer .component__instruction{
    background: none !important;
}

.mediaContainer .component__instruction-inner {
    font-family: 'FSDillonProRegular' !important;
    //font-size: 1rem;
    font-size:clamp(1rem, 1rem + 0vw, 1rem);
    font-style: normal;
    font-weight: 400;
    //line-height: 1.25rem;
    line-height:clamp(1.25rem, 1.25rem + 0vw, 1.25rem);
    letter-spacing: 0.02rem;
    padding-top: 0.75rem;
}

.background-colour1 .element-color-static .component__instruction-inner{
    color:#4F6074;
}

.background-colour2 .element-color-static .component__instruction-inner{
    color:#E9EBF1;
}

#wrapper .background-colour1 .mediaContainer .youtube__transcript-container,#wrapper .background-colour1 .mediaContainer .vimeo__transcript-container{
    background-color: #ffffff !important;
    color: #041C39 !important;
}

#wrapper .background-colour2 .mediaContainer .youtube__transcript-container,#wrapper .background-colour2 .mediaContainer .vimeo__transcript-container{
    //background-color: #323231 !important;
    background-color: #404040 !important;
    color: #ffffff !important;
}

.mediaContainer .element-color-control {
    //background-color: #ffffff !important;
    background-color:inherit !important;
    //color: #041C39 !important;
    color:inherit !important;
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-family: 'FSDillonProBold' !important;
    font-size: clamp(1.125rem, 1.1rem + 0.125vw, 1.25rem);
    //line-height: 1.5rem;
    line-height:clamp(1.5rem, 1.5rem + 0vw, 1.5rem);
    margin-bottom:0 !important;
    padding: 1rem 1.5rem !important;
}

.mediaContainer .youtube__transcript-body-inline, .mediaContainer .vimeo__transcript-body-inline {
    background-color:inherit !important;
}

.mediaContainer .inline-transcript-open{
    //padding: 0px 1.5rem 1.5rem !important;
    padding: 1.5rem 1.5rem !important;
    color:inherit !important;
}

.mediaContainer .inline-transcript-open *{
    font-family: 'FSDillonProRegular' !important;
    font-size: clamp(1.125rem, 1.1rem + 0.125vw, 1.25rem) !important;
    //line-height: 1.5rem !important;
    line-height:clamp(1.5rem, 1.5rem + 0vw, 1.5rem) !important;
    margin:0 !important;
}

#wrapper .mediaContainer .youtube__transcript-btn[aria-expanded="false"] .icon:before,
#wrapper .mediaContainer .vimeo__transcript-btn[aria-expanded="false"] .icon:before
{
    content: "\e95f" !important;  
}

#wrapper .mediaContainer .youtube__transcript-btn[aria-expanded="false"] .icon,
#wrapper .mediaContainer .vimeo__transcript-btn[aria-expanded="false"] .icon
{
    top: 1px !important;  
}

#wrapper .mediaContainer .youtube__transcript-btn[aria-expanded="true"] .icon:before,
#wrapper .mediaContainer .vimeo__transcript-btn[aria-expanded="true"] .icon:before
{
    content: "\e962" !important;
}

#wrapper .mediaContainer .youtube__transcript-btn[aria-expanded="true"] .icon,
#wrapper .mediaContainer .vimeo__transcript-btn[aria-expanded="true"] .icon
{
    top: 0 !important;
}

#wrapper .mediaContainer .youtube__transcript-btn .icon:before,
#wrapper .mediaContainer .vimeo__transcript-btn .icon:before
{
    line-height: 1rem !important;
    font-size: 1rem !important;
}

#wrapper .mediaContainer .youtube__transcript-container,
#wrapper .mediaContainer .vimeo__transcript-container
{
    border:2px solid var(--border-primary--button-border-input-field, #AEBDE6);
    border-radius: 4px;
}

#wrapper .mediaContainer .youtube__transcript-btn,
#wrapper .mediaContainer .vimeo__transcript-btn
{
    margin:0 !important;
    //border:2px solid var(--border-primary--button-border-input-field, #AEBDE6);
    border-radius: 4px !important;
}

#wrapper .mediaContainer .youtube__transcript-btn:hover, #adapt #wrapper .mediaContainer .youtube__transcript-container button:hover,
#wrapper .mediaContainer .vimeo__transcript-btn:hover, #adapt #wrapper .mediaContainer .vimeo__transcript-container button:hover
{
    background-color: #E9EBF1 !important;
    color: #041c39 !important;
}

#wrapper .mediaContainer .youtube__transcript-btn-icon,
#wrapper .mediaContainer .vimeo__transcript-btn-icon
{
    padding: 2px !important;
    width: max-content !important;
    height: max-content !important;
    border: 2px solid;
    border-radius: 100%;
}

#wrapper .background-colour1 .mediaContainer .youtube__transcript-btn-icon,
#wrapper .background-colour1 .mediaContainer .vimeo__transcript-btn-icon
{
    border-color:#041C39;
}

#wrapper .background-colour2 .mediaContainer .youtube__transcript-btn-icon,
#wrapper .background-colour2 .mediaContainer .vimeo__transcript-btn-icon
{
    border-color:#ffffff;
}

#wrapper .background-colour2 .mediaContainer .youtube__transcript-btn:hover .youtube__transcript-btn-icon,
#wrapper .background-colour2 .mediaContainer .vimeo__transcript-btn:hover .vimeo__transcript-btn-icon
{
    border-color:#041C39;
}

#wrapper .background-colour1 .mediaContainer .youtube__transcript-btn-icon .icon,
#wrapper .background-colour1 .mediaContainer .vimeo__transcript-btn-icon .icon
{
    color:#041C39 !important;
    position:relative;
    top:1px;
}

#wrapper .background-colour2 .mediaContainer .youtube__transcript-btn-icon .icon,
#wrapper .background-colour2 .mediaContainer .vimeo__transcript-btn-icon .icon
{
    color:#ffffff !important;
    position:relative;
    top:1px;
}

#wrapper .background-colour2 .mediaContainer .youtube__transcript-btn:hover .youtube__transcript-btn-icon .icon,
#wrapper .background-colour2 .mediaContainer .vimeo__transcript-btn:hover .vimeo__transcript-btn-icon .icon
{
    color:#041C39 !important;
}


//--------------------------------------------------------
.icon {
    -webkit-transform: none !important;
    color: #AAB0C0;
    height: 1.5rem;
    width: 1.5rem;
}

#wrapper .page .background-colour1.article .element-color-text-icon, #wrapper .page .background-colour1-before.article .element-color-text-icon, #wrapper .page .background-colour1.article .element-color-text-icon .icon, #wrapper .page .background-colour1-before.article .element-color-text-icon .icon {
    color: #AAB0C0;
}


#wrapper .mcq .mcq__inner .mcq__widget .mcq-item label.is-selected {
    background-color: #E9EBF1;
    color: #E9EBF1;
    border-color: #1E438E;
}
//----------------------------------------------------------
// Grapic 
//----------------------------------------------------------

.graphicContainer .graphic__longdescription{
    display:none;
}


.graphic__title, 
.graphic__title-inner, 
.graphic__instruction, 
.graphic__instruction-inner{
    padding:0;
    margin:0;
}

.graphicContainer .graphic__title{
    font-family: FSDillonProBold !important;
    font-style: normal !important;
    line-height: 36px !important;
    font-size: 1.666rem !important;
}

.graphicContainer .graphic__inner{
    padding: 0;
    display: flex;
    flex-direction: column;
    margin-top: 24px;
}

//----------------------------------------------------------
// Next gen footer
//----------------------------------------------------------

.nextStepFooterContainer .component__body{
    padding: 0;
    background-color: transparent !important;
}

.nextStepFooterContainer .block__inner{
    padding:0;
}

// ---------------------------------------------------------
// Course complete
// ---------------------------------------------------------

.mandatory-alert-box {
  display: flex;
  padding: 2rem;
  gap: 1.75rem;
  align-self:stretch;
  align-items: center;
  justify-content: center;
  border: 2px solid #F1A7A3;
  border-radius: 4px;
  background-color: #F8D3D1;
}

.course-complete-alert-box {
  display: flex;
  padding: 2rem;
  //padding: 32px;
  gap: 1.75rem;
  //gap: 28px;
  align-self:stretch;
  border:2px solid #039855;
  border-radius: 4px;
  background-color: #ECFDF3;
}

.course-complete-alert-box *,
.mandatory-alert-box *
{
    display:flex;
    flex-direction: row !important;
    padding:0;
    margin:0;
    gap: 1.75rem;
    //align-items: center;
}

.course-complete-alert-box p,
.mandatory-alert-box p
{
  font-family:'FSDillonProBold' !important;
  color: #041C39 !important;
  //font-size:1.25rem !important;
  font-size:clamp(1.25rem, 1.25rem + 0vw, 1.25rem) !important;
  //font-size:20px;
  font-style: normal !important;
  font-weight: 700 !important;
  //line-height: 1.5rem !important;
  line-height:clamp(1.5rem, 1.5rem + 0vw, 1.5rem) !important;
  //line-height: 24px;
  align-items: center;
}

.course-complete-alert-icon {
    color: #00a86b;
    font-size: 24px;
    margin-right: 12px;
}

.course-complete-alert-content {
    color: #041C39;
    font-family: FSDillonProRegular;
    font-size: 14px;
    line-height: 1.4;
}

//----------------------------------------------------------
//---Slider and Confidence Slider-------------------------------------------------
//----------------------------------------------------------


.background-colour1 .slider .slider__inner .slider__widget .slider__item-input-track,
.background-colour2 .slider .slider__inner .slider__widget .slider__item-input-track{
    //background-color: #E9EBF1 !important;
}


.background-colour1 .confidenceslider .slider__inner .slider__widget .slider__item-input-track,
.background-colour2 .confidenceslider .slider__inner .slider__widget .slider__item-input-track{
    //background-color: #E9EBF1 !important;
}

.slider .slider__inner .slider__widget.is-submitted.is-incorrect .slider__item-input-fill,
.slider .slider__inner .slider__widget.is-submitted.is-correct .slider__item-input-fill,
.background-colour1 .slider .slider__inner .slider__widget .slider__item-input-fill,
.background-colour2 .slider .slider__inner .slider__widget .slider__item-input-fill{
    background-color: #AEBDE6 !important;
}

.confidenceslider .slider__inner .slider__widget.is-submitted.is-incorrect .slider__item-input-fill,
.confidenceslider .slider__inner .slider__widget.is-submitted.is-correct .slider__item-input-fill,
.background-colour1 .confidenceslider .slider__inner .slider__widget .slider__item-input-fill,
.background-colour2 .confidenceslider .slider__inner .slider__widget .slider__item-input-fill{
    background-color: #AEBDE6 !important;
}

//.confidenceslider .slider__inner .slider__widget.is-submitted.is-correct .slider__number-selection, 
.confidenceslider .slider__inner .slider__widget.is-submitted.is-correct .slider__item-input-fill, 
.confidenceslider .slider__inner .slider__widget.is-submitted.is-correct .slider__handle
{
   // background-color: #039855 !important;
}

.background-colour1 .slider .slider__inner .slider__widget.is-submitted.is-correct .slider__number-selection,
.background-colour1 .confidenceslider .slider__inner .slider__widget.is-submitted.is-correct .slider__number-selection{
    color: #fff !important;
   // background-color: #039855 !important;
}

.background-colour2 .slider .slider__inner .slider__widget.is-submitted.is-correct .slider__number-selection,
.background-colour2 .confidenceslider .slider__inner .slider__widget.is-submitted.is-correct .slider__number-selection{
    //color: #039855 !important;
    //background-color: #ECFDF3 !important;
}

.background-colour1 .slider .slider__inner .slider__widget.is-submitted.is-incorrect .slider__number-selection,
.background-colour1 .confidenceslider .slider__inner .slider__widget.is-submitted.is-incorrect .slider__number-selection{
    //color: #fff !important;
    //background-color: #DD221A !important;
}

.background-colour2 .slider .slider__inner .slider__widget.is-submitted.is-incorrect .slider__number-selection,
.background-colour2 .confidenceslider .slider__inner .slider__widget.is-submitted.is-incorrect .slider__number-selection{
    //color: #DD221A !important;
    //background-color: #FCE9E8 !important;
}

.background-colour1 .slider .slider__scale-notch-container,
.background-colour1 .slider .slider__scale-container,
.background-colour1 .slider .slider__number
{
    //background-color: #1E438E !important;
    background-color: #FFFFFF !important;
}

.background-colour1 .confidenceslider .slider__scale-notch-container,
.background-colour1 .confidenceslider .slider__scale-container,
.background-colour1 .confidenceslider .slider__number
{
    //background-color: #1E438E !important;
    background-color: #FFFFFF !important;
}

.background-colour1 .slider .slider__scale-notch{
    //background-color: #1E438E !important;
    background-color: #FFFFFF !important;
}

.background-colour1 .confidenceslider .slider__scale-notch{
    //background-color: #1E438E !important;
    background-color: #FFFFFF !important;
}

.background-colour1 .slider__label-start-inner,
.background-colour1 .slider__label-end-inner
{
    color: #ffffff !important;
}

.background-colour2 .slider .slider__scale-notch-container,
.background-colour2 .slider .slider__scale-container,
.background-colour2 .slider .slider__number
{
    background-color: #E9EBF1 !important;
}

.background-colour2 .confidenceslider .slider__scale-notch-container,
.background-colour2 .confidenceslider .slider__scale-container,
.background-colour2 .confidenceslider .slider__number
{
    background-color: #E9EBF1 !important;
}

.background-colour2 .slider .slider__scale-notch{
    background-color: #E9EBF1 !important;
}

.background-colour2 .confidenceslider .slider__scale-notch{
    background-color: #E9EBF1 !important;
}

.slider .slider__number{
    font-family: 'FSDillonProBold' !important;
    font-size:1rem !important;
    color:#FFF !important;
}

//.confidenceslider .slider__inner .slider__widget.is-submitted.is-correct .slider__number-selection{,
.slider .slider__inner .slider__widget .slider__number-selection,
.confidenceslider .slider__inner .slider__widget .slider__number-selection{
    font-family: 'FSDillonProBold' !important;
    font-size:1rem !important;
    box-shadow:none !important;
    border-radius: 4px !important;
    height: 1.5rem !important;
    padding: 0 4px !important;
    //background-color: #323231 !important;
    background-color: #404040 !important;
}

.background-colour1 .slider .slider__inner .slider__widget.is-submitted.is-correct .slider__number-selection,
.background-colour1 .slider .slider__inner .slider__widget.is-submitted.is-incorrect .slider__number-selection,
.background-colour1 .slider .slider__inner .slider__widget .slider__number-selection,
.background-colour1 .confidenceslider .slider__inner .slider__widget .slider__number-selection{
    color:#FFF !important;
    background-color: #404040 !important;
}

.background-colour2 .slider .slider__inner .slider__widget.is-submitted.is-correct .slider__number-selection,
.background-colour2 .slider .slider__inner .slider__widget.is-submitted.is-incorrect .slider__number-selection,
.background-colour2 .slider .slider__inner .slider__widget .slider__number-selection,
.background-colour2 .confidenceslider .slider__inner .slider__widget .slider__number-selection{
    color:#011228 !important;
    background-color: #FFF !important;
}

.confidenceslider .slider__number{
    font-family: 'FSDillonProBold' !important;
    font-size:1rem !important;
    color:#FFF !important;
}

.slider__label-start-inner,.slider__label-end-inner{
    font-family: 'FSDillonProBold' !important;
    //font-size: 1rem !important;
    font-size:clamp(1rem, 1rem + 0vw, 1rem) !important;
    letter-spacing: 0.02rem !important;
    //line-height:1.25rem !important;
    line-height:clamp(1.25rem, 1.25rem + 0vw, 1.25rem) !important;
}

.confidenceslider .slider__inner .slider__widget .slider__item-input-fill-linked{
    background-color: #ffffff !important;
}


.slider .slider__inner .slider__widget{
   //padding: 1.25rem 1.5rem !important;
   margin-top: 1.5rem !important;
   padding-top: 1.25rem !important;
   padding-bottom: 0 !important;
   padding-left: 0 !important;
   padding-right: 0 !important;
   border-radius: 4px;
}

.confidenceslider .slider__inner .slider__widget{
   //padding: 1.25rem 1.5rem !important;
   margin-top: 1.5rem !important;
   padding-top: 1.25rem !important;
   padding-bottom: 0 !important;
   padding-left: 0 !important;
   padding-right: 0 !important;
   border-radius: 4px;
}

.background-colour1 .slider .slider__inner .slider__widget{
  //background-color: #E9EBF1 !important;
  background-color: #515D7A !important;
}

.background-colour2 .slider .slider__inner .slider__widget{
  //background-color: #1B1B1A !important;
  background-color: #373737 !important;
}


.background-colour1 .confidenceslider .slider__inner .slider__widget{
  //background-color: #E9EBF1 !important;
  background-color: #515D7A !important;
}

.background-colour2 .confidenceslider .slider__inner .slider__widget{
  //background-color: #1B1B1A !important;
  background-color: #373737 !important;
}

//-----------------------------------------------------------
//---Stacker-------------------------------------------------
//-----------------------------------------------------------

.stacker__item-text-inner{
    padding:0 !important;
}

.stacker .stacker__widget {
    margin-top:1.25rem !important;
}

.stacker__widget:not(.stacker__not-sliding) .stacker__item-sorter {
    display: none !important;
}

.stacker__item-image-text{
    display: flex;
    align-items: center;
    padding: 1rem 3.25rem;
    background-color: #515D7A !important;
    color: #ffffff;
    font-family: 'FSDillonProRegular' ;
    //font-size: 1.125rem !important;
    font-size:clamp(1.125rem, 1.125rem + 0vw, 1.125rem) !important;
    font-style: normal;
    font-weight: 400;
    //line-height: 1.5rem !important; 
    line-height:clamp(1.5rem, 1.5rem + 0vw, 1.5rem) !important;
    letter-spacing: 0.003rem !important;
}

.stackerContainer .component__title,
.stackerContainer .component__title *{
    font-style: normal !important;
    font-family: FSDillonProBold !important;
    //font-size:1.669rem !important;
    font-size:clamp(1.6688rem, 1.6688rem + 0vw, 1.6688rem) !important;
    //line-height: 2.25rem !important; 
    line-height:clamp(2.25rem, 2.25rem + 0vw, 2.25rem) !important;
    letter-spacing: 0.002rem !important;
    background: transparent !important;
    padding: 0 !important;
}

.stackerContainer .component__body-inner p{
    margin: 8px 0 !important;
}

.stackerContainer .component__instruction-inner{
    margin-bottom:1.5rem;
}

.stacker__item-navigation {
    opacity:0.8;
    background-color:#E9EBF1 !important;
}

.stacker__item-navigation:hover {
    background-color:#00539F !important;
}

.stacker__item-navigation:hover .icon {
    color: #ffffff !important;
}

.stacker__item-navigation .icon {
    color: #0068B2 !important;
}

.stackerContainer .js-a11y-completion-description {
    display: none;
}


.stacker__not-sliding .stacker{
    display: flex;
    flex-direction: column;
    gap: 1rem;
}


.background-colour1 .stacker__not-sliding .stacker .stacker__item-image-text{
    background-color: #fff !important;
    border: 2px solid #AEBDE6;
    border-radius: 4px;
    color:#041C39;
}

.background-colour2 .stacker__not-sliding .stacker .stacker__item-image-text{
    background-color: rgba(255, 255, 255, 0.10) !important;
    border: 2px solid #AEBDE6;
    border-radius: 4px;
    color:#FFF;
}

.stacker__not-sliding .stacker__item-sorter-index
{
    font-size: 1rem;
    //font-weight: bold;
    border-radius: 50%;
    padding: 0 5px !important; 
    font-family: 'FSDillonProBold' !important;
}

.stacker__not-sliding .stacker__item-sorter-picker-selector{
    font-size: 1rem;
    //padding: 0 5px !important; 
    font-family: 'FSDillonProRegular' !important;
}

.background-colour1 .stacker__not-sliding .stacker__item-sorter-picker-selector{
    color: #323231;
}

.background-colour2 .stacker__not-sliding .stacker__item-sorter-picker-selector{
    color: #FFFFFF;
}

.background-colour1 .stacker__not-sliding .stacker__item-sorter-index
{
    color: #323231;
    border: 2px solid #323231;
}

.background-colour2 .stacker__not-sliding .stacker__item-sorter-index
{
    color: #FFFFFF;
    border: 2px solid #FFFFFF;
}

#wrapper .page .background-colour1.article .stacker__not-sliding .element-color-icon-dynamic .icon{
    color:#024597;
}

#wrapper .page .background-colour2.article .stacker__not-sliding .element-color-icon-dynamic .icon{
    color:#FFFFFF;
}

#wrapper .page .stacker__not-sliding .element-color-icon-dynamic .stacker__item-sorter-index:hover,
#wrapper .page .stacker__not-sliding .element-color-icon-dynamic .icon:hover
{
    color:inherit;
}


.stacker__not-sliding .stacker__item-sorter{
    display: flex;
    flex-direction: column;
    width: 3.4rem !important;
    height: 3.4rem !important;
    left: 0.875rem !important;
    align-items: center;
    justify-content: center;
    background-color: transparent !important;
}


.stacker__not-sliding .stacker__item-sorter:hover{
    background-color: #00539F !important;
    color:#ffffff !important;
}

.stacker__not-sliding .stacker__item-sorter:hover .stacker__item-sorter-index{
    color: #FFFFFF !important;
    border: 2px solid #FFFFFF !important;
}

#wrapper .page .background-colour1.article .stacker__not-sliding .element-color-icon-dynamic.stacker__item-sorter:hover .icon,
#wrapper .page .background-colour2.article .stacker__not-sliding .element-color-icon-dynamic.stacker__item-sorter:hover .icon{
    color: #FFFFFF !important;
}

.stacker__not-sliding .stacker__item-image-text{
    padding: 1rem 3.75rem;
}

.stacker__inner .stacker__widget.stacker__not-sliding .stacker__item-sorter i{
   height:auto !important; 
}

.stacker__inner .stacker__widget.stacker__not-sliding .stacker__item-sorter-picker-selector{
    height:1.75rem;
    width:1.75rem;
    border: 1px solid #AEBDE6 !important;
    background-color: #FFF !important;
    color:#323231 !important;
}

.stacker__inner .stacker__widget.stacker__not-sliding .stacker__item-sorter-picker-selector:first-child{
   // border-top: 1px solid #AEBDE6;
}

.stacker__inner .stacker__widget.stacker__not-sliding .stacker__item-sorter-picker-selector:hover{
    background-color: #00539F !important;
    color:#ffffff !important;
}

.stacker__inner .stacker__widget.stacker__not-sliding .stacker__item-sorter-picker{
    left:2.5rem;
}

.stacker__inner .stacker__widget.stacker__not-sliding .stacker__item-sorter-picker .stacker__item-sorter-picker-inner{
   border-radius:0;
}

.stacker__inner .stacker__widget.stacker__not-sliding .stacker__item-sorter-picker .stacker__item-sorter-picker-pin{
    display:none;
}

.stacker__inner .stacker__widget .stacker__item-marking {
    margin: 0 !important;
}

.stacker__inner .stacker__widget.show-user-answer .stacker__item-marking-is-correct,
.stacker__inner .stacker__widget.show-user-answer .stacker__item-marking-is-incorrect{
    transform: translate(0, -50%) !important;
}

.stacker__inner .stacker__widget.show-user-answer .stacker__item-marking-is-correct:before,
.stacker__inner .stacker__widget.show-user-answer .stacker__item-marking-is-incorrect:before{
    box-shadow:none !important;
    font-size: 1rem !important;
    font-weight: bold !important;
    display: flex;
    align-items: center;
    justify-content: center;
    height:1.5rem;
    width:1.5rem;
}

.stacker__inner .stacker__widget.show-user-answer .stacker__item-marking-is-incorrect:before{
    color: #DD221A !important;
    background: #fff !important;
    border: 2px solid #DD221A !important;
    outline: 3px solid #fff;
}

.stacker__inner .stacker__widget.show-user-answer .stacker__item-marking-is-correct:before{
    color: #039855 !important;
    background: #fff !important;
    border: 3px solid #039855 !important;
    outline: 3px solid #fff;
}

//----------------------------------------------------------
// Fill in the blanks
//----------------------------------------------------------

.fillintheblanks .select2 {
    box-shadow: none !important;
    border: 2px solid #AEBDE6 !important;
    border-radius:4px !important;
    top:0 !important;
}

.fillintheblanks .select2.select2-container--disabled{
    margin-right: 2.5rem !important;
}

.fillintheblanks .select2-container--focus,.fillintheblanks .select2-container--open {
    border-color:#355699 !important;
}

.background-colour2 .fillintheblanks .select2 {
 background-color: rgba(255, 255, 255, 0.10) !important;
}

.background-colour1 .fillintheblanks .select2 {
 background-color: transparent !important;
}

.background-colour1 .fillintheblanks .select2:hover,
.background-colour2 .fillintheblanks .select2:hover {
 background-color: #F3F3F3 !important;
}


.fillintheblanks__widget ul,
.fillintheblanks__widget li:not(.select2-results__option),
.fillintheblanks__widget p,
.fillintheblanks__widget div,
{
    //font-size: 1.25rem !important;
    font-size:clamp(1.25rem, 1.25rem + 0vw, 1.25rem) !important;
    font-family: 'FSDillonProRegular' !important;
    margin:0;
    padding:0;
}

.fillintheblanks__widget{
    padding:1.5rem 0 !important;
    background-color:transparent !important;
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
}

.background-colour1 .fillintheblanks__widget ul,
.background-colour1 .fillintheblanks__widget li:not(.select2-results__option),
.background-colour1 .fillintheblanks__widget p,
.background-colour1 .fillintheblanks__widget div,
{
    color:#4F6074 !important;
}

.background-colour2 .fillintheblanks__widget ul,
.background-colour2 .fillintheblanks__widget li:not(.select2-results__option),
.background-colour2 .fillintheblanks__widget p,
.background-colour2 .fillintheblanks__widget div,
{
    color:#E9EBF1 !important;
}


#wrapper .fillintheblanks .select2-selection__arrow{
    background-color:transparent !important;
}

#wrapper .background-colour2 .fillintheblanks .select2:hover .select2-selection__arrow,
#wrapper .background-colour1 .fillintheblanks .select2-selection__arrow{
    color:#0068B2 !important;
}

#wrapper .background-colour2 .fillintheblanks .select2-selection__arrow{
    color:#FFFFFF !important;
}

.select2-dropdown{
    top:100%;
    border-color: #355699;
    border-width: 2px;
}

.select2-results__options{
    padding: 0 !important;
}

.select2-selection__rendered{
    font-size: 1.25rem;
    font-family: 'FSDillonProBold' !important;
}

.background-colour1 .select2-selection__rendered {
    color: #041C39 !important;
}

.background-colour2 .select2-selection__rendered {
    color:#E9EBF1 !important;
}

.select2-results__option{
    font-size: 1.25rem;
    font-family: 'FSDillonProRegular' !important;
    color: #041C39 !important;
    background-color: #E9EBF1 !important;
    margin:2px 0 !important;
    padding-left: 0.625rem;
    padding-right: 0.625rem;
}

.select2-results__option:first-child{
    margin-top:0 !important;
}

.select2-results__option:last-child{
    margin-bottom:0 !important;
}

.select2-results__option--highlighted{
    color: #FFFFFF !important;
    background-color: #1E438E !important;
}

.select2-dropdown .select2-results__option:first-child{
   display: none !important;
}

#wrapper .fillintheblanks .select2-selection__rendered{
    line-height: 1.2rem !important;
}

.filInBlanksContainer .component__title,
.filInBlanksContainer .component__title *{
    font-style: normal !important;
    font-family: FSDillonProBold !important;
    font-size:1.669rem !important;
    line-height: 2.25rem !important; 
    letter-spacing: 0.002rem !important;
    background: transparent !important;
    padding: 0 !important;
}

.filInBlanksContainer .component__instruction{
    margin-top: 1rem !important;
}

.fillintheblanks__body-inner .H6,
.fillintheblanks__body-inner .Sub-Headline{
    padding-bottom: 8px !important;
}

.background-colour1 .fillintheblanks__item-control.is-incorrect~span.for-marking{
    background-color:#DD221A !important;
    color:#FFFFFF !important;
    border: 2px solid #FFFFFF;
    outline: 3px solid #DD221A;
}

.background-colour1 .fillintheblanks__item-control.is-correct~span.for-marking{
    background-color:#039855 !important;
    color:#FFFFFF !important;
    border: 2px solid #FFFFFF;
    outline: 3px solid #039855;
}

.background-colour2 .fillintheblanks__item-control.is-incorrect~span.for-marking{
    color:#DD221A !important;
    background-color:#FFFFFF !important;
    border: 2px solid #DD221A;
    outline: 3px solid #FFFFFF;
}

.background-colour2 .fillintheblanks__item-control.is-correct~span.for-marking{
    color:#039855 !important;
    background-color:#FFFFFF !important;
    border: 2px solid #039855;
    outline: 3px solid #FFFFFF;
}

.fillintheblanks__item-control.is-correct~span.for-marking,
.fillintheblanks__item-control.is-incorrect~span.for-marking
{
   display: flex !important;
   align-items: center;
   justify-content: center;
   font-weight: bold !important;
   box-shadow:none !important;
   width: 1.25rem !important;
   height: 1.25rem !important;
}

.fillintheblanks span.for-marking{
    top: 50% !important;
    transform: translate(-50%, -50%) !important;
}

.fillintheblanks__item-control.is-correct~span.for-marking.icon:before,
.fillintheblanks__item-control.is-incorrect~span.for-marking.icon:before{
    font-size:0.75rem !important;
    font-weight:bold !important;
}

#wrapper .fillintheblanks .use-validation-colors .fillintheblanks__item-control.is-incorrect~.select2 .select2-selection__rendered {
    color: #DD221A !important;
}

#wrapper .fillintheblanks .use-validation-colors .fillintheblanks__item-control.is-incorrect~.select2{
    border-color: #EE908C !important;
    background-color: #FCE9E8 !important;
}

#wrapper .fillintheblanks .use-validation-colors .fillintheblanks__item-control.is-correct~.select2 .select2-selection__rendered {
    color: #039855 !important;
}

//#wrapper .fillintheblanks .use-validation-colors:not(:first-child) .fillintheblanks__item-control.is-correct~.select2 {
#wrapper .fillintheblanks .use-validation-colors .fillintheblanks__item-control.is-correct~.select2 {
    border-color: #D1FADF !important;
    background-color: #ECFDF3 !important;
}

#wrapper .background-colour1 .fillintheblanks .use-validation-colors .fillintheblanks__item-control.is-correct~.select2 .select2-selection__arrow,
#wrapper .background-colour1 .fillintheblanks .use-validation-colors .fillintheblanks__item-control.is-incorrect~.select2 .select2-selection__arrow,
#wrapper .background-colour2 .fillintheblanks .use-validation-colors .fillintheblanks__item-control.is-correct~.select2 .select2-selection__arrow,
#wrapper .background-colour2 .fillintheblanks .use-validation-colors .fillintheblanks__item-control.is-incorrect~.select2 .select2-selection__arrow
{
    color: #0068B2 !important;
}
//----------------------------------------------------------
// Assesment------------------------------------------------
//----------------------------------------------------------

.is-assessment .article__title{
    display:block;
}

.is-assessment .redUnderline{
    display:flex;
    margin-top:-2px;
    margin-bottom:12px;
}

.is-assessment .article__body {
    margin-bottom: 32px !important;
}

.is-assessment .article__body-inner {
    background: transparent !important;
    padding: 0 !important;
}

.is-assessment .article__body-inner p {
    font-family: 'FSDillonProRegular' !important;
    font-size: 1.25rem;
    font-style: normal;
    font-weight: 400;
    line-height:1.5rem;
    letter-spacing: 0.02rem;
    margin:0;
} 

.is-assessment.background-colour1 .article__body-inner {
    color: #4F6074 !important;
}

.is-assessment.background-colour2 .article__body-inner {
    color: #E9EBF1 !important;
}

.is-assessment .article__title-inner,
.is-assessment .article__title-inner *{
    font-family: FSDillonProBold !important;
    font-style: normal !important;
    // font-size: 2.221rem !important;
    // font-size: 2.22rem !important;
    // line-height: 2.5rem !important;
    // letter-spacing: .004rem !important;
    font-size: 1.669rem !important;
    line-height: 2.25rem !important;
    letter-spacing: .002rem !important;
    background: transparent !important;
    padding: 8px 0 !important;
}

.is-assessment .article__title-inner:before {
    display:none;
}

.is-assessment .block:not(:first-child):not(:last-child) .block__inner{
    border-top: none !important;
    border-bottom: none !important;
    border-radius: 0 !important;
}

.is-assessment .block:last-child .block__inner{
    border-top: none !important;
    border-top-left-radius: 0 !important;
    border-top-right-radius: 0 !important;
}

.is-assessment .block:first-child .block__inner{
    border-bottom: none !important;
    border-bottom-left-radius: 0 !important;
    border-bottom-right-radius: 0 !important;
}

  .is-assessment .block:not(:last-child) .component__container:after {
    border: none;
    height: 2px;
    content: '';
    display: block;
    position: relative;
    top: 2.5rem;
    width: 100%;
}

.background-colour1.is-assessment .component__container:after {
    background: linear-gradient(180deg, #CED1DA 0%, #D7DCEA 100%);
}

.background-colour2.is-assessment .component__container:after {
    background: linear-gradient(180deg, #5F5F5F 0%, #403F3F 98.77%);
}


.is-assessment .block:not(:last-child) .component__container{
  //  background: linear-gradient(180deg, #5F5F5F 0%, #403F3F 98.77%);
}

.questionNumber{
    font-family: FSDillonProRegular !important;
    font-style: normal;
    color: #041C39 !important;
    font-weight: 700;
    line-height: 20px;
    font-size: 1rem;
    letter-spacing: 0.02;
    text-decoration: none;
    padding: 4px 12px;
    background-color: #D2D9E8;
    border-radius: 4px;
    width: auto !important;
    align-items: center;
    gap: 4px;
    display: flex;
    width: max-content !important;
}
//----------------------------------------------------------
// Branching
//----------------------------------------------------------

.branching__item-col{
    width:100% !important;
}

.branching .branching__inner .branching__item{
    background: none !important;
    border: none !important;;
}

.background-colour1 .branching__item-inner{
    background-color: #FFFFFF;
    border: 1px solid #CED1DA;
    border-radius: 4px;
}

.background-colour2 .branching__item-inner{
    background-color: #404040;
    border: 1px solid #5F5F5F;
    border-radius: 4px;
}

.branching .branching__inner .branching__item{
    //border:none !important;
    //background:transparent !important;
}

.branching__item-narrative-body{
    padding:0 !important;
}

.branching__item-col-2-inner {
    padding:0 3rem !important;
    padding-bottom: 3rem !important;
}


.branching__item-narrative{
    padding: 1rem 3rem !important;
}

#adapt #wrapper .background-colour1 .branching button.branching__item-reset,
#adapt #wrapper .background-colour1 .branching button.branching__item-retry,
#adapt #wrapper .background-colour1 .branching button.branching__item-branches-button {
    background: transparent;
    color: #041C39;
    border: 2px solid #AEBDE6;
    font-size: 1.25rem;
    line-height: 1.5rem;
    font-family: 'FSDillonProRegular' !important;
}

#adapt #wrapper .background-colour2 .branching button.branching__item-reset,
#adapt #wrapper .background-colour2 .branching button.branching__item-retry,
#adapt #wrapper .background-colour2 .branching button.branching__item-branches-button {
    background: rgba(255, 255, 255, 0.10);
    color: #FFFFFF;
    border: 2px solid #AEBDE6;
    font-size: 1.25rem;
    line-height: 1.5rem;
    font-family: 'FSDillonProRegular' !important;
}

#adapt #wrapper .branching button.branching__item-branches-button {
        text-align: left;
}

#adapt #wrapper .branching button.branching__item-reset:hover,
#adapt #wrapper .branching button.branching__item-retry:hover,
#adapt #wrapper .branching button.branching__item-branches-button:hover,
#adapt #wrapper .branching button.branching__item-branches-button:focus{
    background-color: #F3F3F3 !important;
    color: #041C39 !important;
}

.branching__item-narrative-title,
.branching__item-feedback-breakdown-title
{
    font-family: 'FSDillonProBold' !important;
    padding-left: 0 !important;
    padding-right: 0 !important;
    font-size: 1.66rem !important;
}

.background-colour1 .branching__item-narrative-title,
.background-colour1 .branching__item-feedback-breakdown-title
{
color: #041C39 !important;
}

.background-colour2 .branching__item-narrative-title,
.background-colour2 .branching__item-feedback-breakdown-title
{
color: #FFFFFF !important;
}

.branching__item-narrative-title:after {
    border: none;
    height: 2px;
    content: '';
    display: block;
    position: relative;
    top: 0.5rem;
    width: 100%;
}

.background-colour1 .branching__item-narrative-title:after {
    background: linear-gradient(180deg, #D7D7D7 0%, #E9E9E9 100%);
}

.background-colour2 .branching__item-narrative-title:after {
    background: linear-gradient(180deg, #D7D7D7 0%, #E9E9E9 100%);
}

.branching__item-question-title,
.branching__item-question-title p {
    padding: 0 !important;
    font-size: 1.25rem !important;
    font-weight: 700 !important;
    font-family: 'FSDillonProBold' !important;
    line-height: 1.5rem !important;
    letter-spacing: 0.02rem !important;
}

.branching__item-narrative-body p:last-child{
    margin-bottom: 0 !important;
}

.background-colour1 .branching__item-question-title,
.background-colour1 .branching__item-question-title p {
    color: #041C39 !important;
}

.background-colour2 .branching__item-question-title,
.background-colour2 .branching__item-question-title p {
    color: #FFFFFF !important;
}

.background-colour1 .branching__item-narrative-body p,
.background-colour1 .branching__item-narrative-body div,
.background-colour1 .branching__item-narrative-body span,
.background-colour1 .branching__item-narrative-body ul,
.background-colour1 .branching__item-narrative-body li {
    font-family: 'FSDillonProRegular' !important;
    font-size: 1.25rem !important;
    color: #4F6074 !important;
    line-height:1.5rem !important;
}

.background-colour2 .branching__item-narrative-body p,
.background-colour2 .branching__item-narrative-body div,
.background-colour2 .branching__item-narrative-body span,
.background-colour2 .branching__item-narrative-body ul,
.background-colour2 .branching__item-narrative-body li {
    font-family: 'FSDillonProRegular' !important;
    font-size: 1.25rem !important;
    color: #E9EBF1 !important;
    line-height:1.5rem !important;
}

.background-colour1 .branching__item-feedback-body p,
.background-colour1 .branching__item-feedback-body div,
.background-colour1 .branching__item-feedback-body span,
.background-colour1 .branching__item-feedback-body ul,
.background-colour1 .branching__item-feedback-body li,
.background-colour1 .branching__item-feedback-breakdown-item,
.background-colour1 .branching__item-feedback-breakdown-item p,
.background-colour1 .branching__item-feedback-breakdown-item div,
.background-colour1 .branching__item-feedback-breakdown-item span,
.background-colour1 .branching__item-feedback-breakdown-item ul,
.background-colour1 .branching__item-feedback-breakdown-item li,
{
    font-family: 'FSDillonProRegular' !important;
    font-size: 1.25rem !important;
    color: #041C39 !important;
    line-height:1.5rem !important;
}


.background-colour2 .branching__item-feedback-body p,
.background-colour2 .branching__item-feedback-body div,
.background-colour2 .branching__item-feedback-body span,
.background-colour2 .branching__item-feedback-body ul,
.background-colour2 .branching__item-feedback-body li,
.background-colour2 .branching__item-feedback-breakdown-item,
.background-colour2 .branching__item-feedback-breakdown-item p,
.background-colour2 .branching__item-feedback-breakdown-item div,
.background-colour2 .branching__item-feedback-breakdown-item span,
.background-colour2 .branching__item-feedback-breakdown-item ul,
.background-colour2 .branching__item-feedback-breakdown-item li,
{
    font-family: 'FSDillonProRegular' !important;
    font-size: 1.25rem !important;
    color: #E9EBF1 !important;
    line-height:1.5rem !important;
}

.branching .branching__inner .branching__item-feedback-breakdown-item {
    padding: 1rem 1.5rem !important;
}

.branching .branching__inner .branching__item-feedback-breakdown-item:last-child {
    margin-bottom: 1.5rem !important;
}

.branching__item-feedback-breakdown-item
{
 border-radius: 4px !important;
 border: 2px solid #AEBDE6 !important;
}

.branching .branching__inner .branching__item-branches-button {
    margin-bottom: 1rem !important;
}

.branching__item-feedback-breakdown-item-answer{
    font-weight: 700 !important;
}

//----------------------------------------------------------
// Matching Question
//----------------------------------------------------------
.matching .matching__inner .matching__widget .matching-item{
    display: flex;
    flex-direction: column;
    gap: 1rem;
    padding: 1rem 0;
    border-top: 1px dashed #D7D7D7;
}

.matching .matching__inner .matching__widget .matching-item__title{
    padding: 0 !important;
}

.matching-item__title_inner{
    font-family: 'FSDillonProBold' !important;
    font-size: 1.25rem;
    //font-size: clamp(1.125rem, 1.225rem, 1.25rem);
    font-style: normal;
    font-weight: 400;
    line-height:1.5rem;
    letter-spacing: 0.02rem;
}

.background-colour1 .matching-item__title_inner 
{
    color:#041C39;
}

.background-colour2 .matching-item__title_inner
{
    color:#E9EBF1;
}

.matching-item__select-container .dropdown__btn{
    border: 2px solid #AEBDE6 !important;
    border-radius: 4px !important;
}

.matching-item__select-container .dropdown__btn[aria-expanded="true"]{
    border-color: #355699 !important;
}

.matching-item__select-container .dropdown__btn .dropdown__inner{
   // padding: 12px 12px 12px 16px;
   padding: 0.75rem 0.75rem 0.75rem 1rem !important;
   display: flex;
   align-items: center;
   font-family: 'FSDillonProRegular' !important;
   font-size: 1.25rem !important;
   //font-size: clamp(1.125rem, 1.225rem, 1.25rem);
   font-style: normal;
   font-weight: 400;
   line-height:1.5rem !important;
   letter-spacing: 0.02rem !important;
}

.matching-item__select-container .dropdown__btn.is-selected .dropdown__inner{
    font-family: 'FSDillonProBold' !important;
}

.background-colour1 .matching-item__select-container .dropdown__btn .dropdown__inner{
    color:#4F6074 !important;
    background-color: transparent !important;
}

//.background-colour1 .matching-item__select-container .dropdown__btn:hover,
//.background-colour2 .matching-item__select-container .dropdown__btn:hover{
//    border-color: #355699 !important;
//}

.background-colour1 .matching-item__select-container .dropdown__btn:hover .dropdown__inner,
.background-colour2 .matching-item__select-container .dropdown__btn:hover .dropdown__inner
{
    color:#041C39 !important;
    background-color: #F3F3F3 !important;
}

.background-colour2 .matching-item__select-container .dropdown__btn .dropdown__inner{
    color:#E9EBF1 !important;
    background-color: rgba(255, 255, 255, 0.10) !important;
}

.background-colour2 .matching .matching__inner .matching__widget .matching-item__select-container .dropdown__btn:hover .dropdown__icon .icon,
.background-colour1 .matching .matching__inner .matching__widget .matching-item__select-container .dropdown__icon .icon{
    color:#0068B2;
}

.background-colour2 .matching .matching__inner .matching__widget .matching-item__select-container .dropdown__icon .icon{
    color:#ffffff;
}

.matching .matching__inner .matching__widget .matching-item__select-container .dropdown__icon .icon:before{
    font-size:1.25rem !important;
}

.matching .matching__inner .matching__widget .matching-item__select-container .dropdown ul{
    border: 2px solid !important;
    border-color: #1E438E !important;
    border-radius: 4px;
    padding:0 !important;
    border-top: none !important;
}

.matching .matching__inner .matching__widget .matching-item__select-container .dropdown .dropdown-item,
.matching .matching__inner .matching__widget .matching-item__select-container .dropdown .dropdown-item .dropdown-item__inner{
   font-family: 'FSDillonProRegular' !important;
   font-size: 1.25rem !important;
   //font-size: clamp(1.125rem, 1.225rem, 1.25rem);
   font-style: normal;
   font-weight: 400;
   line-height:1.5rem !important;
   letter-spacing: 0.02rem !important;
   color: #041C39 !important;
}

.matching .matching__inner .matching__widget .matching-item__select-container .dropdown-item[aria-selected="true"]{
    border: none !important;
    background-color: #E9EBF1 !important;
}

.matching .matching__inner .matching__widget .matching-item__select-container .dropdown ul li:hover {
    background-color: #1E438E !important;
}

.matching .matching__inner .matching__widget .matching-item__select-container .dropdown ul li:hover .dropdown-item__inner{
    color: #FFFFFF !important;
}

#wrapper .matching .matching__inner .matching__widget.is-submitted .matching-item__select-container .matching-item__select-state .matching-item__select-incorrect-icon .icon:before {
    padding: .25rem;
    background-color: #DD221A;
    color: #ffffff;
    font-weight: bold;
    box-shadow: none;
    font-size: 1.25rem;
}

#wrapper .matching .matching__inner .matching__widget.is-submitted .matching-item__select-container .matching-item__select-state .matching-item__select-correct-icon .icon:before {
    padding: .25rem;
    background-color: #039855;
    color: #ffffff;
    font-weight: bold;
    box-shadow: none;
    font-size: 1.25rem;
}

#wrapper .matching .matching__inner .matching__widget.is-submitted .matching-item__select-container .matching-item__select-state .matching-item__select-icon{
   transform: translate(-50%, -65%) !important; 
}


.matching-item.is-correct .dropdown__btn{
    border-color: #D1FADF !important;
}

.matching-item.is-correct .dropdown__btn .dropdown__inner{
    color: #039855 !important;
    background: #ECFDF3 !important;
}

.matching-item.is-incorrect .dropdown__btn{
    border-color: #EE908C !important;
}

.matching-item.is-incorrect .dropdown__btn .dropdown__inner{
    color: #DD221A !important;
    background: #FCE9E8 !important;
}

.matching__widget{
    margin-top: 1.5rem !important;
}
//----------------------------------------------------------
// Reveal---------------------------------------------------
//----------------------------------------------------------

.reveal__widget-control{
    width: 3.125rem;
    height: 3.125rem;
    top:50% !important;
    transform: translateY(-50%);
    background-color: #E9EBF1 !important;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
    opacity:0.8;
}

.reveal__widget-control .reveal__widget-icon{
    color:#0068B2 !important;
    transform: translateY(-50%) !important;
}

.reveal__widget-control:hover{
    background-color: #0068B2 !important;
}

.reveal__widget-control:hover .reveal__widget-icon {
    color: #FFFFFF !important;
}

.reveal .reveal__inner .reveal__widget-item-text-body,
.reveal .reveal__inner .reveal__widget-item-text-body p,
.reveal .reveal__inner .reveal__widget-item-text-body ul{
    //color:#E9EBF1 !important;
    color:#FFFFFF !important;
    font-family: 'FSDillonProRegular' !important;
    font-size: 1.25rem;
    //font-size: clamp(1.125rem, 1.225rem, 1.25rem);
    font-style: normal;
    font-weight: 400;
    line-height:1.5rem;
    letter-spacing: 0.02rem;
    margin: 0.75rem 0 !important;
}

.reveal .reveal__inner .reveal__widget-item-text{
    display: flex !important;
    align-items: center !important;
    justify-content: center !important;
    flex-direction: column;
}

.reveal .reveal__inner .reveal__widget-item-text button.reveal__popup-open{
    width: 100% !important;
    padding: 0.5rem !important;
    border-radius: 4px !important;
    border: 2px solid #AEBDE6 !important;
    margin-top: 0.25rem !important;
    margin-bottom: 0 !important;
    font-family: 'FSDillonProRegular' !important;
    color: #FFFFFF !important;
    font-size: 1rem !important;
    letter-spacing: 0.002rem !important;
    background-color: transparent !important;
}

.background-colour1 .reveal .reveal__widget-item-text-container,
.background-colour2 .reveal .reveal__widget-item-text-container {
    background-color: rgba(50, 50, 49, 0.7) !important;
}

//----------------------------------------------------------
// Text Input-----------------------------------------------
//----------------------------------------------------------

.textinput .textinput__inner .textinput__widget .textinput-item__textbox{
    padding: 0.75rem 1rem !important;
    border-radius: 4px !important;
    border: 2px solid #AEBDE6 !important;
    font-family: 'FSDillonProRegular' !important;
    color: #1B1B1A !important;
    font-size: 1rem !important;
    letter-spacing: 0.002rem !important;
    line-height: 1.25rem !important;
}

.textinput .textinput__inner .textinput__widget .textinput-item__textbox:-internal-autofill-selected,
.textinput .textinput__inner .textinput__widget .textinput-item__textbox:focus{
    border-color: #355699 !important;
    background-color: #F3F3F3 !important;
}

.textinput .textinput__inner .textinput__widget .is-incorrect .textinput-item__textbox:-internal-autofill-selected,
.textinput .textinput__inner .textinput__widget .is-incorrect .textinput-item__textbox{
    color: #DD221A !important;
    font-weight: 700;
    background-color: #FCE9E8 !important;
    border-color: #EE908C !important;
}


.textinput .textinput__inner .textinput__widget.show-correct-answer .is-incorrect .textinput-item__textbox:-internal-autofill-selected,
.textinput .textinput__inner .textinput__widget.show-correct-answer .is-incorrect .textinput-item__textbox{
    color: #039855 !important;
    font-weight: 700;
    background-color: #ECFDF3 !important;
    border-color: #D1FADF !important;
}

.textinput .textinput__inner .textinput__widget .is-correct .textinput-item__textbox:-internal-autofill-selected,
.textinput .textinput__inner .textinput__widget .is-correct .textinput-item__textbox{
    color: #039855 !important;
    font-weight: 700;
    background-color: #ECFDF3 !important;
    border-color: #D1FADF !important;
}

.textinput .textinput__inner .textinput__widget .textinput-item__placeholder {
    font-family: 'FSDillonProRegular' !important;
    color: #1B1B1A !important;
    font-size: 1rem !important;
    letter-spacing: 0.002rem !important;
    line-height: 1.25rem !important;
}

.textinput .component__widget{
    margin: 1.25rem 0;
}

//----------------------------------------------------------
// Hidden hotspots------------------------------------------
//----------------------------------------------------------

.hiddenhotspots__pin{
    background-color:#1E438E !important;
    border:4px solid #FFFFFF;
}


.hiddenhotspots__pin:not(.is-correct):not(.is-incorrect):hover{
   background-color: #323231 !important;
}

.hiddenhotspots__pin .icon,
.hiddenhotspots__pin .icon::before{
    color:#FFFFFF !important;
}


.hiddenhotspots__pin.is-correct:hover,
.hiddenhotspots__pin.is-incorrect:hover{
    background-color: #1E438E !important;
}

.hiddenhotspots__pin.is-correct:hover .icon::before,
.hiddenhotspots__pin.is-incorrect:hover .icon::before{
   // color:#FFFFFF !important;
}

.hiddenhotspots__item-counter{
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 16px 52px;
    background-color: #515D7A !important;
    color: #ffffff;
    font-family: 'FSDillonProRegular';
    font-size: 1.25rem !important;
    font-style: normal;
    font-weight: 700;
    line-height: 1.5rem !important;
    letter-spacing: .003rem !important;
}


.hiddenhotspots__zone{
    background-color: #1E438E !important;
    border: 4px solid #FFFFFF;
    border-radius: 50%;
    height: 3.125rem !important;
    width: 3.125rem !important;
}


.hiddenhotspots__mobile-navigation{
    background-color: #E9EBF1 !important;
    height:3.5rem;
}

.hiddenhotspots__mobile-navigation button{
    display: flex !important;
    align-items:center;
    justify-content:center;
    padding: 0;
    margin: 0;
    background-color: #E9EBF1 !important;
}

.hiddenhotspots__mobile-navigation button:hover,
.hiddenhotspots__mobile-navigation button:focus
{
    background-color: #E9EBF1 !important;
}

.hiddenhotspots__mobile-navigation button i:before {
    color: #1E438E !important;
    font-weight: bold;
    font-size: 1.625rem !important;
}

.hiddenhotspots__mobile-navigation button i.icon-arrow-left:before {
    content: "\e960" !important;
}

.hiddenhotspots__mobile-navigation button i.icon-arrow-right:before {
    content: "\e961" !important;
}

//----------------------------------------------------------
// Reference List-------------------------------------------
//----------------------------------------------------------

.referencelist__body .referencelist__body-inner p {
    font-family: 'FSDillonProRegular' !important;
    font-size: 1.25rem;
    font-style: normal;
    font-weight: 400;
    line-height: 1.5rem;
    letter-spacing: .02rem;
    margin:0;
    padding: 1em 0;
    display:flex;
    flex-direction: column;
    gap: 0.5rem;
}

.referencelist__body .referencelist__body-inner p:not(:last-child){
    border-bottom: 1px solid #AEBDE6;
}

.referencelist__body .referencelist__body-inner p a{
    font-family: 'FSDillonProRegular' !important;
    font-size: 1rem;
    font-style: normal;
    font-weight: 400;
    line-height: 1.25rem;
    letter-spacing: 0.02rem;
    text-decoration-line: underline;
    text-decoration-style: solid;
    text-decoration-skip-ink: none;
    text-decoration-thickness: auto;
    text-underline-offset: auto;
    text-underline-position: from-font;
}

.background-colour1 .referencelist__body .referencelist__body-inner p a,
.background-colour1 .referencelist__body .referencelist__body-inner p a:hover,
.background-colour1 .referencelist__body .referencelist__body-inner p a:focus,
.background-colour1 .referencelist__body .referencelist__body-inner p a:visited{
    color: #024597 !important;
}

.background-colour2 .referencelist__body .referencelist__body-inner p a,
.background-colour2 .referencelist__body .referencelist__body-inner p a:hover,
.background-colour2 .referencelist__body .referencelist__body-inner p a:focus,
.background-colour2 .referencelist__body .referencelist__body-inner p a:visited{
   // color: #F0F1F4 important;
   color: #AEBDE6 !important;
}

.referencelist__header-inner{
    display: flex;
    flex-direction: column;
    gap: 0.75rem;
}

.referencelist__header-inner .referencelist__title{
    order:1;
}

.referencelist__header-inner .referencelist__instruction{
    order:2;
}

.referencelist__header-inner .referencelist__body{
    order:3;
}

.referencelist .element-color-static {
    background-color: transparent !important;
    padding:0 !important;
}

.referencelist .component__title-inner,
.referencelist .component__title-inner *
{
//color: #041C39 !important;
font-family: 'FSDillonProBold' !important;
//font-size: 26.7px;
font-size: 1.669rem !important;
font-style: normal !important;
font-weight: 700 !important;
//line-height: var(--font-Headline-XS-Line-Height, 36px); /* 134.831% */
line-height: 2.25rem !important;
letter-spacing: 0.002rem !important;
padding:0 !important;
margin:0!important;
}

.referencelist__body-inner{
    padding:0 !important;
    display: flex;
    flex-direction: column;
}

.referenceListContainer .block__inner {
    padding-bottom:0 !important;
}

//----------------------------------------------------------
// ED & I Banner 
//----------------------------------------------------------

.ediComponent .component__body{
    padding:0 !important;
    border-radius:4px;
    background-color: transparent !important;
}
.ediComponent .component__body-inner{
    display: flex;
    flex-direction: row;
    padding:0 !important;
    background-color: #ffffff;
    border-radius: 6px;
    border: 2px solid #AEBDE6;
}

.ediComponent .contentSection,
.ediComponent .imageSection{
    width:100%;
}

.ediComponent .contentSection{
 padding:2rem 3rem;    
 display: flex;
 flex-direction: column;
 justify-content: center;
 gap: 0.25rem;
 min-height: 288px;
}

.ediComponent .contentSection p{
    margin: 0.75rem 0 !important;
}

.ediComponent .contentSection .body{
    color:#4F6074 !important;
}

.ediComponent .contentSection .title{
    color:#041C39 !important;
}

.ediComponent .imageSection{
    background-image:url('https://adaptassets.learningpool.com/football_association/assets/68/13/6813f0d03f99ac4798539138.png');
    background-size: cover;
    min-height: 15rem;
    height: auto;
}

.surveyLink,
.surveyLink:hover,
.surveyLink:focus {
    width: 100%;
    display: flex !important;
    align-items: center;
    justify-content: center;
    padding: 0.75rem;
    color: #fff !important;
    border-radius: 4px;
    text-decoration: none !important;
    font-size: 1rem;
    font-family: 'FSDillonProRegular' !important;
    font-weight: 400;
    line-height: 1.25rem;
    cursor: pointer;
}

.surveyLink,
.surveyLink:focus{
    background-color: #E1261C !important;
    border: 1px solid #E1261C !important;
}

.surveyLink:hover{
    background-color: #00539f !important;
    border: 1px solid #00539f !important;
}

#adapt #app #wrapper .background-colour1 .ediComponent .component__inner .customlink,
#adapt #app #wrapper .background-colour1 .ediComponent .component__inner .customlink:hover,
#adapt #app #wrapper .background-colour1 .ediComponent .component__inner .customlink:focus,
#adapt #app #wrapper .background-colour1 .ediComponent .component__inner .customlink:visited,
#adapt #app #wrapper .background-colour2 .ediComponent .component__inner .customlink,
#adapt #app #wrapper .background-colour2 .ediComponent .component__inner .customlink:hover,
#adapt #app #wrapper .background-colour2 .ediComponent .component__inner .customlink:focus,
#adapt #app #wrapper .background-colour2 .ediComponent .component__inner .customlink:visited
{
    color: #fff !important;
}



#adapt #app #wrapper .ediComponent .component__inner .customlink:hover{
    background-color: #00539f !important;
    color: #fff !important;
    text-decoration: none !important;
}



//----------------------------------------------------------
// Image gallery
//----------------------------------------------------------
.imagegallery__image-container .imagegallery__image-inner img{
    max-height:100% !important;
}

.imagegallery__image-container .imagegallery__image-inner{
    width: 100% !important;
    transform: unset !important;
    top: 0 !important;
    max-width: 100% !important;
}

.imagegallery__image-container .imagegallery__image{
    height: 100% !important;
    width: 100% !important;
}

html.no-touch .imagegallery__image-container{
    height: 100% !important;
}

.imagegallery__image-container{
    height: auto !important;
    //height: 100% !important;
}

html.size-large .imagegallery__image-container{
    height: auto !important;
    padding: 0 !important;
}

.imagegallery__controls-is-left{
    margin-left: 0 !important;
}

.imagegallery__controls-is-right{
    margin-right: 0 !important;
}

.imagegallery__controls-is-left{
    width: 3.125rem !important;
    height: 3.125rem !important;
    //display: flex !important;
    //align-items: center;
    //justify-content: center;
    border-top-right-radius: 4px !important;
    border-bottom-right-radius: 4px !important;
    padding:0 !important;
    background-color: #E9EBF1 !important;
    opacity: 0.8 !important;
    margin-bottom: 0 !important;
}

.imagegallery__controls-is-right{
    width: 3.125rem !important;
    height: 3.125rem !important;
    //display: flex !important;
    //align-items: center;
    //justify-content: center;
    border-top-left-radius: 4px !important;
    border-bottom-left-radius: 4px !important;
    padding:0 !important;
    background-color: #E9EBF1 !important;
    opacity: 0.8 !important;
    margin-bottom: 0 !important;
}

.imagegallery__controls-is-right .icon,
.imagegallery__controls-is-left .icon
{
    width: 100% !important;
    color: #0068B2 !important;
}


html.no-touch .imagegallery__buttons, html.no-touch .imagegallery__controls{
    opacity: 1 !important;
}

.imagegallery__image-container .imagegallery__buttons button{
    opacity: 1 !important;
    background-color: #E9EBF1 !important;
}

.imagegallery__image-container .imagegallery__buttons .imagegallery__button-toggle-thumbs {
    background-image: url('https://adaptassets.learningpool.com/football_association/assets/67/da/67da93a580915048803f065b.svg');
}

//.imagegallery__image-container .imagegallery__buttons .imagegallery__button-toggle-thumbs[title="Hide thumbnails"],
.imagegallery__image-container .imagegallery__buttons .imagegallery__button-toggle-thumbs:hover
{
    background-image: url('https://adaptassets.learningpool.com/football_association/assets/67/da/67da93a43a93e4e66054a1c8.svg');
}

.imagegallery__image-container .imagegallery__buttons .imagegallery__button-popout {
    background-image: url('https://adaptassets.learningpool.com/football_association/assets/67/da/67da93a549d86edec37fb5e5.svg');
}

.imagegallery__image-container .imagegallery__buttons .imagegallery__button-popout:hover {
    background-image: url('https://adaptassets.learningpool.com/football_association/assets/67/da/67da9a1557e6bd90bab57ce9.svg');
}

.imagegallery__image-container .imagegallery__buttons .imagegallery__button-show-thumbs {
    background-image: url('https://adaptassets.learningpool.com/football_association/assets/67/dc/67dc2c8900a2aeec666a149e.svg');
}

.imagegallery__image-container .imagegallery__buttons .imagegallery__button-show-thumbs:hover {
    background-image: url('https://adaptassets.learningpool.com/football_association/assets/67/dc/67dc2c888ddbf39c9cf0f51d.svg');
}

.imagegallery__thumbs-container .imagegallery__thumbs .imagegallery__thumb{
    //width: 6.25rem !important;
    //height: 3.563rem !important;
    box-shadow:none !important;
    aspect-ratio: 100/57 !important;
}

.imagegallery__thumbs-container .imagegallery__thumbs .imagegallery__active-marker{
    border: 3px solid #AEBDE6 !important;
}

.imagegallery__image-container .imagegallery__image-inner{
    box-shadow:none !important;
}

.imagegallery__image-container .imagegallery__image-inner .imagegallery__image-text{
    width: 100% !important;
    left: 0 !important;
    right: 0 !important;
    text-shadow:none !important;
    transition:.25s .2s ease-in-out !important;
    padding:1.25rem !important;
}

.imagegallery__image-container .imagegallery__image-inner.hover .imagegallery__image-text{
   background: linear-gradient(180deg, rgba(4, 28, 57, 0.00) 6.2%, #00060C 100%);
}

.imagegallery__image-container .imagegallery__image-inner .imagegallery__image-text-inner .imagegallery__image-title{
    font-family: 'FSDillonProBold' !important;
    font-style: normal !important;
    font-size: 1.66rem !important;
    line-height: 2.25rem !important;
    letter-spacing: .002rem !important;
}

.imagegallery__image-container .imagegallery__image-inner .imagegallery__image-text .imagegallery__image-caption,
.imagegallery__image-container .imagegallery__image-inner .imagegallery__image-text .imagegallery__image-counter{
    font-family: 'FSDillonProRegular' !important;
    font-size: 1.25rem !important;
    font-style: normal !important;
    font-weight: 400 !important;
    line-height: 1.5rem !important;
    letter-spacing: .02rem !important;
}

html.touch .imagegallery__buttons,
.touch .imagegallery__buttons{
    top:0.625rem !important;
}

html.touch .imagegallery.component.state-thumbs .imagegallery__buttons,
.touch .imagegallery.component.state-thumbs .imagegallery__buttons {
    opacity:1 !important;
}

.touch .imagegallery__thumbs-container,
html.touch .imagegallery__thumbs-container
{
    top:0 !important;
    height: 100% !important;
    background-color: #e9ebf1 !important;
}
//----------------------------------------------------------
// YES/NO
//----------------------------------------------------------

.yesno__section-inner{
    padding: 0 !important;
    background: transparent !important;
}

.yesno__title, .yesno__score{
    padding: 0 !important;
    margin: 0 !important;
    font-family: FSDillonProBold !important;
    font-style: normal !important;
    font-size: 1.669rem !important;
    line-height: 2.25rem !important;
    letter-spacing: .002rem !important;
}


.yesno__instruction,.yesno__instruction *{
    margin: 0 !important;
    font-family: 'FSDillonProRegular' !important;
    font-size: 1rem;
    font-style: normal;
    font-weight: 400;
    line-height: 1.25rem; /* 125% */
    letter-spacing: 0.02rem;
}

.yesno__instruction {
    padding: 0 !important;
}

.yesno__instruction{
    padding-top: 0.75rem !important;
    position:relative !important;
}

.yesno__instruction:after{
    border:none;
    height:1px;
    content: '';
    display: block;
    left: 0;
    position: absolute;
    top: 0;
    width: 100%;
}

.background-colour1 .yesno__instruction:after{
    background:linear-gradient(180deg, #CED1DA 0%, #D7DCEA 100%);
}

.background-colour2 .yesno__instruction:after{
    background:linear-gradient(180deg, #5F5F5F 0%, #403F3F 98.77%);
}

.yesno__body,
.yesno__body p,
.yesno__body ul{
    font-family: 'FSDillonProRegular' !important;
    font-size: 1.25rem;
    //font-size: clamp(1.125rem, 1.225rem, 1.25rem);
    font-style: normal;
    font-weight: 400;
    line-height:1.5rem;
    letter-spacing: 0.02rem;
}

.background-colour1 .yesno__body,
.background-colour1 .yesno__body p,
.background-colour1 .yesno__body ul,
.background-colour1 .yesno__instruction{
    color: #4F6074 !important;
}

.background-colour2 .yesno__body,
.background-colour2 .yesno__body p,
.background-colour2 .yesno__body ul,
.background-colour2 .yesno__instruction{
    color: #E9EBF1 !important;
}

.yesno__widget {
    display: flex;
    flex-direction: row;
    gap: 2rem;
}

.yesno__image-marking-icon{
    display: flex !important;
    align-items: center;
    justify-content: center;
}

.yesno__image-marking-icon .icon{
    display: flex !important;
    align-items: center;
    justify-content: center;
    border-radius: 4px !important;
    box-shadow: 0px 43px 12px 0px rgba(0, 0, 0, 0.00), 0px 28px 11px 0px rgba(0, 0, 0, 0.01), 0px 15px 9px 0px rgba(0, 0, 0, 0.05), 0px 7px 7px 0px rgba(0, 0, 0, 0.09), 0px 2px 4px 0px rgba(0, 0, 0, 0.10) !important;
    padding: 16px 20px !important;
}

.yesno__images-container button.yesno__btn .icon{
    padding: 0 !important;
    width: 0 !important;
    height: 0 !important;
    box-shadow: none !important;
    min-width: fit-content !important;
    min-height: fit-content !important;
    background-color: transparent !important;
}

.yesno__images .yesno__button .yesno__button-label{
  padding:0 !important;
  margin:0 !important;
  background-color: transparent !important;
}

#wrapper.location-page .yesno__images-container button.yesno__btn{
   display: flex;
   align-items: center;
   justify-content: center;
   border-radius:4px;
   padding: 1rem 1.25rem !important;
   gap: 8px;
   box-shadow: 0px 43px 12px 0px rgba(0, 0, 0, 0.00), 0px 28px 11px 0px rgba(0, 0, 0, 0.01), 0px 15px 9px 0px rgba(0, 0, 0, 0.05), 0px 7px 7px 0px rgba(0, 0, 0, 0.09), 0px 2px 4px 0px rgba(0, 0, 0, 0.10);
}

.yesno__image-marking-icon .icon:before,
.yesno__images-container button.yesno__btn .icon:before{
    line-height: 1.24rem !important;
    font-size: 1rem !important;
    font-weight:700 !important;
}


.yesno__inner .yesno__image-marking-icon .icon.icon-tick,
#wrapper.location-page .yesno__images-container button.yesno__yes-btn{
   border: 3px solid #D1FADF !important;
   background-color: #039855 !important;
}

.yesno__inner .yesno__image-marking-icon .icon.icon-cross,
#wrapper.location-page .yesno__images-container button.yesno__no-btn{
   border: 3px solid #FBE1DF !important;
   background-color: #DD221A !important;
}

.yesno__images .yesno__button .yesno__button-label{
font-family: 'FSDillonProRegular' !important;
font-size: 1rem !important;
font-style: normal !important;
font-weight: 700 !important;
line-height: 1.25rem !important;
letter-spacing: 0.02rem !important;
color:#FFFFFF !important;
}

.yesno__images .yesno__image-feedback{
    width: 100% !important;
    height: 100% !important;
    left: 0 !important;
    top: 0 !important;
    box-shadow: none !important;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: rgba(50,50,49,0.7) !important;
    padding: 0 !important;
}


.yesno__images .yesno__image-feedback p,
.yesno.component .not-started .yesno__start-btn button{
color: #FFF !important;
text-align: center;
font-family: 'FSDillonProBold' !important;
//font-size: 35.5px;
font-size: 2.219rem !important;
font-style: normal;
font-weight: 700;
line-height: 2.5rem !important; 
letter-spacing: 0.003rem !important;
}

.yesno__images .yesno__image-feedback .yesno__image-feedback-inner{
    max-width: 50%;
}

.component .yesno__inner .yesno__scroll-buttons.yesno__prev-btn{
    transform: translate(100%, 0) !important;
    border-radius: 0px 4px 4px 0px !important;
}

.component .yesno__inner .yesno__scroll-buttons.yesno__next-btn{
    transform: translate(-100%, 0) !important;
    border-radius: 4px 0px 0px 4px !important;
}

.component .yesno__inner .yesno__scroll-buttons,
.component .yesno__inner .yesno__scroll-buttons:hover{
    background-color: #E9EBF1 !important;
    color: #1E438E !important;
    opacity: 0.8 !important;
}

.component .yesno__inner .yesno__scroll-buttons .icon:before{
    font-weight: 700 !important;
}

.component .yesno__inner .yesno__scroll-indicators{
    display:flex !important;
    align-items: center;
    justify-content: center;
    gap:1rem;
}

.yesno__inner .yesno__scroll-indicators button{
    border: none !important;
    height: 0.5rem !important;
    width: 0.5rem !important;
    margin:0 !important;
}


.background-colour1 .yesno__inner .yesno__scroll-indicators button{
    background-color: #1E438E !important;
}

.background-colour1 .yesno__inner .yesno__scroll-indicators button.is-active{
    background-color: #AAB0C0 !important;
}

.background-colour2 .yesno__inner .yesno__scroll-indicators button{
    background-color: #FFFFFF !important;
}

.background-colour2 .yesno__inner .yesno__scroll-indicators button.is-active{
    background-color: #4F9DFC !important;
}

.yesno__images-container .yesno__images-container-inner:before,
.yesno__images-container .yesno__images-container-inner:after{
    display:none !important;
}

.yesno__images .yesno__image {
    box-shadow: none !important;
}

.yesno.component .not-started .yesno__start-btn button{
    margin: 0 !important;
    box-shadow:none !important;
    background-color: rgba(50,50,49,0.7) !important;
}

.component .yesno__inner .yesno__timer{
    box-shadow: none !important;
    font-family: 'FSDillonProBold' !important;
    
    padding: 0rem 0.625rem !important;
    font-size: 1.669rem !important;
    font-weight: 700 !important;
    line-height: 2rem !important;
    letter-spacing: 0.007rem !important;
    width: auto !important;
    border-radius: 4px !important;
    background-color: #FFF !important;
    color: #011E41 !important;
    margin-top: 1.5rem !important;
}

.yesno__timer-inner .separator{
  top:10%;
}

.component .yesno__inner .yesno__images-container .yesno__image-buttons{
    margin-top: -2rem !important;
}

.OS-ios .yesno__image-marking-icon button, .OS-ios .yesno__button button{
    width: auto !important;
}

.OS-ios .yesno__images .yesno__button{
    margin: 0 0.5rem !important;
}

.yesno.component .challenge .btn__container{
    display: none !important;
}

.yesno.component .not-started .btn__container{
    display: none !important;
}

.yesno__images-container{
   // margin-bottom: 0 !important;
}

//----------------------------------------------------------
// Narrative
//----------------------------------------------------------

.hotGraphicContainer .narrative__slider,
.narrativeContainer .narrative__slider{
    display: flex;
    align-items: center;
}

.hotGraphicContainer .narrative__content,
.narrativeContainer .narrative__content{
    background-color:inherit !important;
}

.hotGraphicContainer .narrative__indicators,
.narrativeContainer .narrative__indicators{
    width:100% !important;
    margin-top:32px;
    display:flex;
    gap:1rem;
}

.narrative .mode-large.narrative__inner .narrative__content-inner .narrative__controls-container {
    display: none;
}

#wrapper .page .background-colour1 .hotGraphicContainer .narrative__progress.is-selected,
#wrapper .page .background-colour1 .narrativeContainer .narrative__progress.is-selected
{
    background-color: #AAB0C0 !important;
    margin:0;
}

#wrapper .page .background-colour2 .hotGraphicContainer .narrative__progress.is-selected,
#wrapper .page .background-colour2 .narrativeContainer .narrative__progress.is-selected{
    background-color: #4F9DFC !important;
    margin:0;
}

#wrapper .page .background-colour1 .hotGraphicContainer .narrative__progress,
#wrapper .page .background-colour1 .narrativeContainer .narrative__progress
{
    background-color: #1E438E !important;
    margin:0;
}

#wrapper .page .background-colour2 .hotGraphicContainer .narrative__progress,
#wrapper .page .background-colour2 .narrativeContainer .narrative__progress{
    background-color: #FFFFFF !important;
    margin:0;
}


.hotGraphicContainer .narrative .narrative__inner .narrative__progress,
.narrativeContainer .narrative .narrative__inner .narrative__progress{
    width:0.75rem !important;
    height:0.75rem !important;
}


.hotGraphicContainer .narrative__progress .icon:before,
.narrativeContainer .narrative__progress .icon:before{
    display:none;
}

.hotGraphicContainer .narrative__instruction .icon:before
.narrativeContainer .narrative__instruction .icon:before{
    display:none;
}

.hotGraphicContainer .narrative__inner .narrative__content-inner,
.narrativeContainer .narrative__inner .narrative__content-inner{
    padding: 0 2rem !important;
}

.hotGraphicContainer .narrative__inner.items-are-full-width .narrative__content-inner,
.narrativeContainer .narrative__inner.items-are-full-width .narrative__content-inner{
    padding: 0 !important;
    margin-top:2rem;
}

.hotGraphicContainer .narrative__inner.items-are-full-width .narrative__indicators
.narrativeContainer .narrative__inner.items-are-full-width .narrative__indicators{
    order:2;
    margin:0;
}

.hotGraphicContainer .narrative__content-title-inner,
.narrativeContainer .narrative__content-title-inner{
    padding: 0 !important;
    margin: 0 !important;
    border: 0 !important;
    //font-style: normal !important;
    //font-weight: 500 !important;
    //font-family: 'FSDillonProBold' !important;
    //font-size: 1.66rem !important;
    //line-height: 2.25rem !important; 
    //letter-spacing: 0.002rem !important;
    
    font-size: 1.25rem !important;
    //font-size: clamp(1.125rem, 1.225rem, 1.25rem);
    font-weight: 400 !important;
    font-style: normal !important;
    line-height:1.5rem !important;
    letter-spacing: 0.02rem !important;
    font-family: 'FSDillonProBold' !important;
}

.hotGraphicContainer .narrative__content-body .redUnderline,
.narrativeContainer .narrative__content-body .redUnderline{
    display:none;
}

.narrativeContainer .component__instruction,
.narrativeContainer .component__instruction-inner{
    padding:0;
}


.narrativeContainer .component__inner{
    display: flex;
    //flex-direction: column-reverse;
    flex-direction: column;
    //margin-top: 8px;
}


.narrativeContainer .component__widget{
    margin-top: 12px;
}


.narrativeContainer .component__instruction{
    background: none !important;
}


.narrativeContainer .component__instruction-inner {
    font-family: 'FSDillonProRegular' !important;
    font-size: 1rem;
    font-style: normal;
    font-weight: 400;
    line-height: 1.25rem;
    letter-spacing: 0.02rem;
    //margin-top:4px;
    padding-top: 0.75rem;
}


.hotGraphicContainer .narrative .narrative__inner .narrative__controls
.hotGraphicContainer .narrative .narrative__inner .narrative__controls,
.narrativeContainer .narrative .narrative__inner .narrative__controls,
.narrativeContainer .narrative .narrative__inner .narrative__controls{
    opacity:0.8;
    background-color:#E9EBF1 !important;
}

.hotGraphicContainer .narrative .narrative__inner .narrative__controls:not(.is-disabled):hover,
.narrativeContainer .narrative .narrative__inner .narrative__controls:not(.is-disabled):hover{
    background-color:#00539F !important;
}


.hotGraphicContainer .narrative .narrative__inner .narrative__controls:not(.is-disabled):hover .icon,
.narrativeContainer .narrative .narrative__inner .narrative__controls:not(.is-disabled):hover .icon{
    color: #ffffff !important;
}

.hotGraphicContainer .narrative .narrative__inner .narrative__controls .icon,
.narrativeContainer .narrative .narrative__inner .narrative__controls .icon{
    color: #0068B2 !important;
}

.hotGraphicContainer .narrative .narrative__inner .narrative__controls.is-disabled .icon,
.narrativeContainer .narrative .narrative__inner .narrative__controls.is-disabled .icon{
    color: #0068B2 !important;
}

.hotGraphicContainer .narrative .narrative__inner .narrative__controls.is-disabled .icon,
.narrativeContainer .narrative .narrative__inner .narrative__controls.is-disabled .icon{
     color: #A3A3A3 !important;
}

.hotGraphicContainer .narrative .narrative__inner .narrative__controls.narrative__controls-right
.narrativeContainer .narrative .narrative__inner .narrative__controls.narrative__controls-right{
    border-radius: 4px 0 0 4px !important;
}

.hotGraphicContainer .narrative .narrative__inner .narrative__controls.narrative__controls-left
.narrativeContainer .narrative .narrative__inner .narrative__controls.narrative__controls-left{
    border-radius: 0 4px 4px 0 !important;
}

.hotGraphicContainer .narrative__slide-container
.narrativeContainer .narrative__slide-container{
    background-color:#1b1b1a;
}

.hotGraphicContainer .narrative__strapline,
.narrativeContainer .narrative__strapline{
    background-color: inherit !important;
}

.hotGraphicContainer .narrative__strapline-btn,
.narrativeContainer .narrative__strapline-btn{
    margin-bottom: 1rem !important;;
    background-color: inherit !important;;
    border: 2px solid #AEBDE6;
    border-radius: 4px;
}

.hotGraphicContainer .narrative__strapline-btn:focus,
.narrativeContainer .narrative__strapline-btn:focus{
    border: 2px solid #AEBDE6;
}

.hotGraphicContainer .narrative__strapline-icon,
.narrativeContainer .narrative__strapline-icon{
     background-color: inherit !important;
}

.hotGraphicContainer .narrative__strapline-title-inner,
.narrativeContainer .narrative__strapline-title-inner{
    font-size: 1.125rem;
    font-style: normal;
    font-weight: 700;
    line-height: 1.5rem;
    letter-spacing: 0.003rem;
    font-family: 'FSDillonProBold' !important;
    padding-left: 1rem !important;
}

.hotGraphicContainer .narrative__strapline-icon .icon:before,
.narrativeContainer .narrative__strapline-icon .icon:before {
    content: "\e95a" !important;
}

.background-colour1 .hotGraphicContainer .narrative__strapline-icon .icon
.background-colour1 .narrativeContainer .narrative__strapline-icon .icon {
    color:#0068B2 !important;
}

.background-colour2 .hotGraphicContainer .narrative__strapline-icon .icon
.background-colour2 .narrativeContainer .narrative__strapline-icon .icon {
    color:#ffffff !important;
}
// ---------------------------------------------------------
// Accordion
// ---------------------------------------------------------


.accordion-item {
    border-radius: var(--spacing-spacing-scale-1, 4px);
    border: 2px solid var(--border-primary--button-border-input-field, #AEBDE6);
    background: rgba(255, 255, 255, 0.10);
    //margin: 8px;
    margin: 8px 0;
    background: #041C39;
}

.accordion-item__title{
    font-family:FSDillonProBold;
    //font-size:20px;
    font-size:clamp(1.125rem, 1.1rem + 0.125vw, 1.25rem);
    line-height:24px;
}

.accordion-item__body p, 
.accordion-item__body ul li,
.accordion-item__body div,
.accordion-item__body a{
    font-family:FSDillonProRegular !important;
    //font-size:20px;
     font-size:clamp(1.125rem, 1.1rem + 0.125vw, 1.25rem);
    line-height:24px;
    margin-top: 0;
}

.accordion-item__body a{
 color:#024597 !important;
}

#wrapper .page .accordion-item .element-color-control{
    background-color: #ffffff !important;
    color: #041c39 !important;
}

#wrapper .page .accordion-item .element-color-control:hover {
    background-color: #E9EBF1 !important;
    color: #041c39 !important;
}

#wrapper .page .accordion-item .element-color-control:hover .icon{
    background-color: #00539F !important;
    border-color: #00539F !important;
    color: #ffffff !important;
}

#wrapper .accordion-item__btn .icon:before {
    position:relative;
}

#wrapper .accordion-item__btn[aria-expanded="false"] .icon:before {
    top: 1px !important;
}

#wrapper .accordion-item__btn[aria-expanded="true"] .icon:before {
    top: 0px !important;
}

#wrapper .accordion-item__btn.is-visited .icon:before {
    content: "\e95f" !important;  
}

#wrapper .accordion-item__btn.is-open .icon:before, .accordion-item__btn.is-selected .icon:before {
    content: "\e962" !important;
}

#wrapper .accordion-item__icon .icon{
    padding: 2px !important;
    width: max-content !important;
    height: max-content !important;
    right: 5% !important;
    top: 32% !important;
    border: 2px solid #041C39;
    border-radius: 100%;
    background-color: #ffffff !important;
    color: #041c39 !important;
}

#wrapper .accordion-item__icon .icon:before{
line-height: 1 !important;
font-size: 1rem !important;
}


// ---------------------------------------------------------
// Gallery
// ---------------------------------------------------------

.imagegallery__image-container .imagegallery__image {
    position: relative;
    display: inline-block;
}

.imagegallery__thumbs-container {
    display: none;
}

.imagegallery__image-container {
    padding-top: 0;
    padding-bottom: 0;
    margin-top: 0;
    margin-bottom: 0;
}

// ---------------------------------------------------------
// Spacing
// ---------------------------------------------------------

.article__inner {
    background: transparent none;
    margin: 0 auto;
    max-width: 100%;
    padding: 8.125rem 0;
}

.accordion-item__body{
    font-size:15px;
}

.article__title {
    display:none;
}

.article ul{
    padding-left:16px;
    margin:0;
}

.article .list{
    font-family: FSDillonProRegular !important;
    line-height: 24px;
    //font-size: 20px;
    font-size: clamp(1.125rem, 1.1rem + 0.125vw, 1.25rem);
}

.flexBox{
    display:flex;
}

.flexBoxNoMargin{
    display: flex;
    margin-bottom: 0;
    margin-top: 0;
}

.dividerBottom{
    height: 2px;
    display: inline-block;
    width: 32px;
    background-color: #DD221A;
}

//------------------------------------
// Media Queries for smaller screens
//-----------------------------------

//Mobile
//@media (max-width: 768px) {
@media (max-width: 539px) {
     .background-image1 {
    background-image: url(@customImage2);
}

.background-image6 {
    background-image:url(@customImage4);
}

//remove later
.hero .HeaderPadding {
    padding-bottom: 17vh;
    padding-top: 17vh;
}

.Module-Hero .block {
    padding-bottom: 17vh;
    padding-top: 17vh;
}

//remove later
.hero .block__inner{
    top: -12vh;
}

.Module-Hero .block__inner{
    top: -12vh;
}

//remove later
.heroDescription{
    padding:0 0;
}

.Module-Hero .Body-Regular,
.Topic-Hero .Body-Regular{
    padding:0 0;
}

.downArrow{
    bottom: -17vh;
}

.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__state {
left: 0.5rem;
}

.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__text-inner {
padding: 0 0 0 1rem;
}

.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__text {
    //padding: .78125rem 2.34375rem .78125rem;
    padding: 0.78rem 1.8rem 0.78rem 2rem !important;
}

//remove later
.HeaderText{
font-size:2.331rem !important;
}

.Module-Hero .Hero-text{
   //font-size:2.331rem !important;
   font-size: clamp(2.3313rem, 2.3313rem + 0vw, 2.3313rem) !important;
}

//remove later
.heroShallow .HeaderText{
   font-size:2.331rem !important;
}

.Topic-Hero .Hero-text{
   //font-size:2.331rem !important;
    font-size:clamp(2.331rem, 2.331rem + 0vw, 2.331rem) !important;
}


.subHeadline{
  font-size:1.35rem !important;
}

.referenceListContainer .block__inner,
.branchingContainer .block__inner,
.hotGraphicContainer .block__inner{
    margin: 0 1rem !important;
    padding: 0 !important;
}

.hotGraphicContainer .component__title,
.hotGraphicContainer .component__body
{
    margin:0 !important;
    padding:0 !important;
    background:transparent !important;
}


.hiddenHotspots .block__inner,
.matchingQuestion .block__inner,
.assesmentResults .block__inner,
.filInBlanksContainer .block__inner,
.stackerContainer .block__inner,
.sliderContainer .block__inner,
.truefalseContainer .block__inner,
.flipCardContainer .block__inner,
.openTextInput .block__inner,
.textinputContainer .block__inner,
.mcqContainer .block__inner,
.graphicalMCQ .block__inner
{
    padding: 2rem !important;
    margin: 0 1rem !important;
}

.no-padding-backgrounds .block__inner{
    margin: 0 1rem !important;
    padding: 0 1rem !important;
}

.is-assessment .article__header-inner{
    margin: 0 1rem !important;
}

.article__inner{
    padding: 3.5rem 0;
}

.ediComponent .block__inner,
.accordionContainer .block__inner,
.yesnoContainer .block__inner,
.imageGalleryContainer .block__inner,
.revealContainer .block__inner,
.mediaContainer .block__inner, 
.graphicContainer .block__inner{
   padding: 0 0.25rem !important;
   margin: 0 1rem !important;
}

.narrativeOuterContainer .article__inner,
.nextStepFooterContainer .article__inner{
    padding: 3.5rem 1.2rem;
}

.nextStepIcon{
    width: 100%;
}

.mandatory-alert-box p{
    width:310%;
}

.truefalse__item-state {
    gap: 1.5rem;
}

.truefalse__item-radio-container {
    padding: .625rem 0 !important;
    width: max-content !important;
    gap: 8px;
}

.truefalse__item-title {
    padding-bottom: 0.25rem !important;
}

.fillintheblanks .select2{
    max-width: 260px !important;
}

.branching__item-narrative {
    padding: 1rem 2rem !important;
}

.branching__item-col-2-inner {
    padding: 0 2rem !important;
    padding-bottom: 2.5rem !important;
}


.yesno__widget {
    flex-direction: column !important;
    gap: 1rem !important;
}

.yesno__section.yesno__images{
    max-width:100% !important;
    margin: 0 !important;
}

.component .yesno__inner .yesno__timer{
    font-size: 1.35rem !important;
    font-style: normal;
    font-weight: 700;
    line-height: 1.5rem !important; 
    letter-spacing: 0.007rem !important;
}

.hiddenhotspots__mobile-navigation {
    display: flex !important;
    align-items: center;
    justify-content:center;
}

.ediComponent .component__body-inner{
    flex-direction:column-reverse !important;
}

.ediComponent .contentSection{
    padding: 1.5rem !important;
    min-height: unset;
}

}

@media (max-width: 47.5rem) {
    .hiddenhotspots__mobile-navigation {
        display: flex !important;
        align-items: center;
        justify-content:center;
    }
}

//other sreens

//remove later
.HeaderText{
font-size:3.95rem;
}

.Module-Hero .Hero-text{
   font-size:3.95rem; 
   font-size: clamp(3.95rem, 3.95rem + 0vw, 3.95rem);
}

//remove later
.heroShallow .HeaderText{
   font-size: 2.96rem;
}

.Topic-Hero .Hero-text{
   //font-size: 2.96rem;
   font-size:clamp(2.96rem, 2.96rem + 0vw, 2.96rem);
}

.subHeadline{
  font-size: 1.666rem;
}


//Tablet
@media (min-width: 540px) and (max-width:1023px){
     .background-image1 {
    background-image: url(@customImage1);
}

.background-image6 {
    background-image: url(@customImage3);
}

//remove later
.hero .HeaderPadding {
    padding-bottom: 17vh;
    padding-top: 17vh;
}

.Module-Hero .block {
    padding-bottom: 17vh;
    padding-top: 17vh;
}

//remove later
.hero .block__inner{
    top: -10vh;
}

.Module-Hero .block__inner{
    top: -10vh;
}

//remove later
.heroDescription{
    padding:0 12%;
}

.Module-Hero .Body-Regular,
.Topic-Hero .Body-Regular
{
    padding:0 12%;
}

.downArrow{
    bottom: -17vh;
}

.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__state {
        left: 1rem;
    }

.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__text-inner {
     padding: 0 0 0 0.2rem;
    }
    
.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__text {
        padding: 1.25rem 3.75rem 1.25rem;
    }
    
.revealContainer .block__inner,     
.mediaContainer .block__inner, 
.graphicContainer .block__inner{
   //padding: 0 0.25rem !important;
   padding: 0  1rem !important;
   //margin: 0 1rem !important;
   margin: 0 2rem !important;
}

.narrativeOuterContainer .article__inner,
.nextStepFooterContainer .article__inner{
   // padding: 3.5rem 1.2rem;
   padding: 8.125rem 3rem;
}
    
}


//Laptops

//@media (min-width:1367px) and (max-width:1440px) {
@media (min-width:1024px) and (max-width:1440px) {
    //remove later
    .hero .HeaderPadding {
    //padding-bottom: 100px;
    //padding-top: 100px;
    padding-bottom: 70px;
    padding-top: 70px;
}

.Module-Hero .block {
    padding-bottom: 70px;
    padding-top: 70px;
}

.downArrow{
    bottom: -70px;
}

.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__state {
        left: 1rem;
    }

.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__text-inner {
     padding: 0 0 0 0.2rem;
    }
    
.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__text {
        padding: 1.25rem 3.75rem 1.25rem;
    }
    
}

@media (min-width:1441px) and (max-width:1600px) {
    
    //remove later
    .hero .HeaderPadding {
   // padding-bottom: 110px;
   // padding-top: 110px;
      padding-bottom: 100px;
      padding-top: 100px;
}

    .Module-Hero .block {
      padding-bottom: 100px;
      padding-top: 100px;
    }

.downArrow{
    bottom: -100px;
}

.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__state {
        left: 1rem;
    }

.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__text-inner {
     padding: 0 0 0 0.2rem;
    }
    
.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__text {
        padding: 1.25rem 3.75rem 1.25rem;
    }
    
}

@media (min-width:1601px) and (max-width:1920px) {

//remove later
.hero .HeaderPadding {
    padding-bottom: 160px;
    padding-top: 160px;
}

.Module-Hero .block {
    padding-bottom: 160px;
    padding-top: 160px;
}

.downArrow{
    bottom: -160px;
}

.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__state {
        left: 1rem;
    }

.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__text-inner {
     padding: 0 0 0 0.2rem;
    }
    
.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__text {
        padding: 1.25rem 3.75rem 1.25rem;
    }
    
}

@media (min-width:1921px) {
    .Module-Hero .block {
      padding-top: 10vw;
      padding-bottom: 10vw;
    }
    
    .downArrow{
    bottom: -10vw;
   }
}

//other resolutions
.mcqContainer .mcq .mcq__inner .mcq__widget .mcq-item__text {
        padding: 1.25rem 3.75rem 1.25rem;
    }
```
