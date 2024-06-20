<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link href="style.css" rel="stylesheet" >
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
    <script>
        $(document).ready(function(){
          $("#show-1").click(function(){
            $("#step-1").css('display', 'flex');
            $("#step-2").css('display', 'none');
            $("#step-3").css('display', 'none');
          });
          $("#show-2").click(function(){
            var inputValue = $("#myInput").val();
            $('#resultContainer').text(inputValue);
            $("#step-2").css('display', 'flex');
            $("#step-1").css('display', 'none')

          });
          $("#show-3").click(function(){
            $("#step-3").css('display', 'flex');
            $("#step-2").css('display', 'none');
          });

          $("#showChat").click(function(){
            $("#chatPopUp").css('display', 'block');
          });
          $("#close").click(function(){
            $("#chatPopUp").css('display', 'none');
          });
          

        });
        </script>
        <style>
        .border {
    border: 1px solid #bbb !important;
}
.Mt2Mb3{
    margin-top: 20px; 
    margin-bottom: 35px;
    padding: 20px 10px;
}
.right-radius{
    border-radius: 10px 0px 0px 10px;
}
.left-radius{
    border-radius: 0px 10px 10px 0px;
}
.device-progressbar{
    background-color: #41b6e6;
}
.card-design {
    position: relative;
    flex-direction: column;
    min-width: 0;
    word-wrap: break-word;
    background-color: #fff;
    background-clip: border-box;
    border: 1px solid rgba(0, 0, 0, .125);
    border-radius: .125rem;
    text-align: center;
}
.cardtop {
    margin-top: 47.5px;
}
.cardtext {
    margin-top: 16px;
    margin-bottom: 47.5px;
    margin-left: 35px;
    margin-right: 35px;
    font-size: 16px;
   
    letter-spacing: .012em;
    color: #444;
}
.ad-width {
    margin-left: 25px;
    margin-right: 25px;
}
#step-1, #step-2, #step-3{
    display: none;
}

#chatPopUp{
    background: #fff;
    width: 240px;
    height: 350px;
    position: absolute;
    right: 0px;
    top: 689px;
    filter: drop-shadow(5px 5px 5px #000000);
    display: none;
}
#chatHeader{
    width: 100%;
    height: 30px;
    background: #000000;
    float: left;
    color: #fff;
    padding: 2px 4px;
}
#close{
    background: transparent;
    color: #fff;
    border: none;
    float: right;
}
.UMH .mh-top .left-column .mh-logo {
    padding: 0;
}
.delltechLogoWrapper svg {
    height: 23px;
    padding: 0;
    width: 182px;
    fill: #0076ce;
}
.mh-flyout-link {
    height: 56px;

}
.mh-label{
    font-size: 14px;
    color: #636363;
    text-transform: none;
}

a{
    text-decoration: none !important;
}
.nav-link{
    color: #000000 !important;
    float: right;
    margin-top: 16px;
}

</style>
    <title>MIAW POC</title>
  </head>
  <body>
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-8 p-4">
                <div class="mh-logo">
                    <a class="delltechLogoWrapper dynamic-link" href="https://www.dell.com/en-us" aria-label="Dell Technologies Home" data-metrics="{&quot;btnname&quot;:&quot;delltechlogo&quot;}"><div><svg class="dellTechLogo mh-show-DeskTop-Tab" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1017 132"><path d="M1015 84.89c0-12.23-6.8-17.66-20.39-20.38-13.58-2.71-21.73-4.08-21.73-13.58 0-6.79 5.43-10.87 14.95-10.87 12.23 0 16.3 5.43 16.3 12.23l1.36 1.36h5.43l1.36-1.36c0-13.58-10.87-19.02-24.46-19.02-14.95 0-23.09 8.15-23.09 17.67 0 10.87 8.15 16.3 21.73 19.02 13.59 2.72 20.38 4.08 20.38 14.95 0 6.79-4.07 12.23-17.66 12.23-12.23 0-17.66-6.8-17.66-14.95l-1.36-1.36h-5.43l-1.36 1.36c0 12.23 9.51 21.74 25.81 21.74 17.66-.02 25.82-8.17 25.82-19.04m-58.42-13.58l1.35-1.36v-4.07c0-19.02-10.87-32.61-29.89-32.61s-29.89 13.59-29.89 32.61v2.71c0 19.02 9.51 35.32 31.25 35.32 19.02 0 25.81-12.23 27.17-20.38l-1.36-1.36h-5.43l-1.36 1.36c-2.72 8.15-8.15 13.59-19.02 13.59-17.67 0-23.1-16.3-23.1-24.45l1.36-1.36h48.92zm-8.15-6.8h-40.76l-1.36-1.36c0-9.51 5.43-23.09 21.74-23.09 16.3 0 21.74 13.58 21.74 23.09l-1.36 1.36zm-59.78 36.68V35.97l-1.36-1.36h-5.43l-1.36 1.36v65.22l1.36 1.36h5.43l1.36-1.36zm0-78.8v-8.15l-1.36-1.36h-5.43l-1.36 1.36v8.15l1.36 1.36h5.43l1.36-1.36zm-51.62 74.73c-13.59 0-21.74-9.51-21.74-28.53s8.15-28.53 21.74-28.53c13.58 0 21.73 9.51 21.73 28.53 0 19.01-8.15 28.53-21.73 28.53m21.73-4.08c0 17.66-4.08 31.25-20.38 31.25-12.23 0-16.3-5.43-17.66-12.23l-1.36-1.36h-5.43l-1.36 1.36c1.36 10.87 9.51 19.02 25.81 19.02 17.67 0 28.53-10.87 28.53-38.04V35.97l-1.36-1.36h-4.08l-1.36 1.36-1.36 8.16h-1.36c-2.71-5.43-9.51-10.87-21.74-10.87-19.02 0-28.53 14.95-28.53 35.33 0 20.37 9.51 35.32 28.53 35.32 12.23 0 19.02-5.43 21.74-10.87h1.37zm-88.3-52.98c13.58 0 23.09 10.87 23.09 28.53s-9.51 28.53-23.09 28.53c-13.59 0-23.1-10.87-23.1-28.53s9.51-28.53 23.1-28.53m0 63.85c17.66 0 31.24-12.23 31.24-35.32s-13.58-35.33-31.24-35.33c-17.67 0-31.25 12.23-31.25 35.33 0 23.09 13.59 35.32 31.25 35.32m-40.76-2.72V8.81l-1.36-1.36h-5.43l-1.36 1.36v92.39l1.36 1.36h5.43l1.36-1.37zm-48.9-61.13c13.58 0 23.09 10.87 23.09 28.53s-9.51 28.53-23.09 28.53c-13.59 0-23.1-10.87-23.1-28.53s9.51-28.53 23.1-28.53m0 63.85c17.66 0 31.25-12.23 31.25-35.32s-13.59-35.33-31.25-35.33-31.25 12.23-31.25 35.33c0 23.09 13.59 35.32 31.25 35.32m-39.4-2.72V60.43c0-17.66-9.51-27.17-24.45-27.17-9.51 0-17.67 4.08-21.74 10.87h-1.36l-1.35-8.16-1.36-1.36h-4.08l-1.36 1.36v65.22l1.36 1.36h5.44l1.35-1.36V64.51c0-14.95 6.8-24.45 21.74-24.45 10.87 0 17.66 6.79 17.66 20.37v40.76l1.36 1.36h5.43l1.36-1.36zm-69.29 0V60.43c0-17.66-9.51-27.17-24.45-27.17-9.51 0-17.66 4.08-21.74 10.87h-1.36V8.81l-1.36-1.36h-5.43l-1.36 1.36v92.39l1.36 1.36h5.43l1.36-1.36V64.51c0-14.95 6.8-24.45 21.74-24.45 10.87 0 17.66 6.79 17.66 20.37v40.76l1.36 1.36h5.44l1.35-1.36zm-116.83-32.6c0-19.02 9.51-28.53 23.09-28.53s19.02 8.15 20.37 16.3l1.36 1.36h5.44l1.36-1.36c-1.36-13.58-12.23-23.09-28.53-23.09-17.66 0-31.24 10.87-31.24 35.33 0 24.45 13.58 35.32 31.24 35.32 16.3 0 27.17-9.51 28.53-23.09l-1.36-1.36h-5.44l-1.36 1.36c-1.36 8.15-6.79 16.3-20.37 16.3-13.59-.01-23.09-9.53-23.09-28.54m-14.95 2.72l1.36-1.36v-4.07c0-19.02-10.87-32.61-29.9-32.61-19.01 0-29.89 13.59-29.89 32.61v2.71c0 19.02 9.51 35.32 31.25 35.32 19.02 0 25.81-12.23 27.17-20.38l-1.36-1.36h-5.43l-1.36 1.36c-2.71 8.15-8.15 13.59-19.02 13.59-17.66 0-23.09-16.3-23.09-24.45l1.36-1.36h48.91zm-8.15-6.8h-40.76l-1.36-1.36c0-9.51 5.43-23.09 21.73-23.09 16.31 0 21.74 13.58 21.74 23.09l-1.35 1.36zm-36.61-51.63V8.81l-1.36-1.36h-70.65l-1.36 1.36v4.08l1.36 1.36h29.89l1.36 1.36v85.59l1.36 1.36h5.43l1.36-1.36V15.6l1.36-1.36h29.89l1.36-1.36zM322.2 83.65v18.9h-61.35V7.45h21.6v76.2h39.75zm-283.65 18.9c22.13 0 40.73-15.12 46.03-35.58l53.8 42.03 53.77-42.01v35.56h61.35v-18.9h-39.75V7.45h-21.6v35.56L140.58 83.3l-11.53-9.01L153.73 55l26.88-21-15.34-12-51.58 40.3-11.53-9.01L153.73 13 138.38 1l-53.8 42.03c-5.3-20.46-23.9-35.58-46.03-35.58H0v95.1h38.55zM21.6 83.65v-57.3h16.95C52.88 26.35 64.5 39.18 64.5 55S52.88 83.65 38.55 83.65H21.6z"></path></svg> 
                    </div>
                </a>
        </div>

            </div>
            <div class="col-md-4">
                <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button" aria-expanded="false">
                    <svg style="width: 16px;" viewBox='0 0 16 16' xmlns='http://www.w3.org/2000/svg'><path d='M8 .942a7.058 7.058 0 1 0 0 14.116A7.058 7.058 0 0 0 8 .942ZM1.908 8.47h2.304c.028.801.122 1.564.278 2.263H2.537a6.053 6.053 0 0 1-.629-2.263Zm6.563-4.145V2.03c.715.263 1.348 1.11 1.782 2.295H8.471Zm2.069.942c.17.692.278 1.458.309 2.262H8.471V5.267h2.068ZM7.53 2.03v2.295H5.748C6.183 3.14 6.816 2.293 7.53 2.03Zm0 3.237v2.262H5.152c.031-.804.14-1.57.31-2.262H7.53ZM4.212 7.529H1.908a6.06 6.06 0 0 1 .629-2.262H4.49c-.157.7-.251 1.461-.279 2.262Zm.94.941H7.53v2.263H5.462a11.35 11.35 0 0 1-.31-2.263Zm2.378 3.204v2.297c-.715-.264-1.347-1.112-1.782-2.297H7.53Zm.94 2.297v-2.297h1.783c-.435 1.186-1.067 2.033-1.782 2.297Zm0-3.238V8.47h2.379c-.031.805-.14 1.57-.31 2.263H8.472ZM11.79 8.47h2.304a6.06 6.06 0 0 1-.629 2.263h-1.953c.157-.7.25-1.462.278-2.263Zm0-.94a12.302 12.302 0 0 0-.278-2.263h1.953c.347.69.566 1.454.628 2.262h-2.303Zm1.089-3.205h-1.63c-.26-.79-.602-1.473-1.008-2.011a6.136 6.136 0 0 1 2.638 2.011ZM5.76 2.315c-.405.538-.747 1.22-1.007 2.01H3.122a6.14 6.14 0 0 1 2.638-2.01Zm-2.638 9.36h1.63c.26.79.602 1.472 1.007 2.01a6.136 6.136 0 0 1-2.637-2.01Zm7.119 2.01c.405-.538.748-1.22 1.007-2.011h1.63a6.131 6.131 0 0 1-2.637 2.011Z' fill='%23636363'/></svg>US/EN</a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">US/EN</a></li>
                  <li><a class="dropdown-item" href="#">PT/BR</a></li>
                </ul>
            </div>
        </div>
      </div>
    <div width="100%" height="150px !important" style="background: linear-gradient(180deg, #006BBD 0%, #64AAE6 100%); overflow: hidden;" id="divBanner" role="main" aria-label="pageTitle">
        <div class="breadcrumb-div-ht pt-4">
            <h1 class="header-text" style="height:150px; color: #FFFFFF; text-align: center; padding-top: 40px; font-weight: normal !important;">Contact Technical Support</h1>
        </div>
    </div>
    <div class="container border Mt2Mb3">
        <div class="container">
            <div class="row">
                <div class="col-11 col-sm-11 col-md-11 col-lg-11 col-xl-11">
                    <div class="mr-md-3 header-ti" style="margin-top: 12px;">
                        <div class="d-flex justify-content-md-start">
                            <svg class="dti dti-xxl" height="32" width="32" viewBox="0 0 32 32">
                                <path xmlns="http://www.w3.org/2000/svg" d="M28.237 20.861v-14.682h-24.474v14.682h-1.956l0.73 4.96h26.921l0.734-4.96h-1.956zM5.645 8.061h20.71v12.8h-20.71v-12.8zM27.834 23.937h-23.672l-0.175-1.195h24.026l-0.179 1.195z"></path>
                            </svg>
                            <h2 class="h5 mb-1 ml-4 mt-1">Technical Issues</h2>
                        </div>
                    </div>
                </div>
                <div class="col-1 col-sm-1 col-md-1 col-lg-1 col-xl-1">
                    <div class="ml-0 ml-md-auto flex-shrink-0 text-center">
                        <div class="mt-2">
                            <button role="link" tabindex="0" aria-label="Close - go to Contact Support homepage" class="btn p-0 close svgiconmargin-top btn_Close" data-dismiss="alert" type="button" data-metrics="{&quot;btnname&quot;:&quot;techissueclose&quot;,&quot;appcode&quot;:&quot;222.830.810.451&quot;}">
                                <svg width="32" height="32" viewBox="0 0 40 40" fill="none">
                                    <path d="M21.668 8.9299L16.01 14.5859L10.354 8.9299L8.94002 10.3439L14.596 15.9999L8.94002 21.6579L10.354 23.0719L16.01 17.4159L21.668 23.0719L23.082 21.6579L17.424 15.9999L23.082 10.3439L21.668 8.9299Z" fill="#006BBD"></path>
                                    <path d="M16 0.993896C7.71202 0.993896 0.994019 7.7119 0.994019 15.9999C0.994019 24.2879 7.71202 31.0059 16 31.0059C24.288 31.0059 31.006 24.2879 31.006 15.9999C31.006 7.7119 24.288 0.993896 16 0.993896ZM16 29.0059C8.82802 29.0059 2.99402 23.1719 2.99402 15.9999C2.99402 8.8279 8.82802 2.9939 16 2.9939C23.172 2.9939 29.006 8.8279 29.006 15.9999C29.006 23.1719 23.172 29.0059 16 29.0059Z" fill="#006BBD"></path>
                                </svg>
                            </button>
                        </div>
                    </div>
                </div>
                <hr class="h-hr mt-4" aria-hidden="true">

            </div>
            <div class="row">
                <div>
                    <div class="row pb-align" style="margin-left: 25px; margin-right: 45px; margin-top: 30px; padding-bottom: 16px;">
                        <div class="col-4 col-sm-4 col-md-4 col-lg-4 col-xl-4 column" id="deviceProgressbarStep1">
                            <div class="progress right-radius device-progressbar">
                                <div class="progress-bar-contactus" id="deviceProgressbar" role="progressbar" aria-label="Identify your device,step 1 of 3" aria-valuenow="0" aria-valuetext="Identify your device,step 1 of 3, 0% completed" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <div class="mt-4">
                                <span class="wizadview xs-hide md-none" id="stepOneDesc" aria-current="step">Identify your device</span>
                            </div>
                        </div>
                        <div class="col-4 col-sm-4 col-md-4 col-lg-4 col-xl-4 column" id="deviceProgressbarStep2">
                            <div class="progress " style="border-radius:0rem !important">
                                <div class="progress-bar-contactus" id="deviceProgressbar_issuetype" role="progressbar" aria-label="Describe your issue,step 2 of 3" aria-valuenow="0" aria-valuetext="Describe your issue,step 2 of 3, 0% completed" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <div class="mt-4">
                                <span class="wizadhide xs-hide md-none" id="stepTwoDesc" aria-current="step">Describe your issue</span>
                            </div>
                        </div>
                        <div class="col-4 col-sm-4 col-md-4 col-lg-4 col-xl-4 column" id="deviceProgressbarStep3">
                            <div class="progress  left-radius">
                                <div class="progress-bar-contactus" id="deviceProgressbar_supportoptions" role="progressbar" aria-label="See your support options,step 3 of 3" aria-valuenow="0" aria-valuetext="See your support options,step 3 of 3, 0% completed" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <div class="mt-4">
                                <span class="wizadhide xs-hide md-none xs-hide" id="stepThreeDesc" aria-current="step">See your support options</span>
                            </div>
                        </div>
                    </div>
                    </div>
                </div>
            </div>
                <div class="row">
                    <h3 class="h3 text-center mt-4">Identify your device</h3>
                </div>
                <div class="row ad-width mb-2 mt-4">
                    <div class="col-sm device-lg-column" id="divDetectPC">
                        <div class="card-design h-100 pointcursor" id="contactusDetectPC" data-metrics="{&quot;btnname&quot;:&quot;detectprod&quot;,&quot;appcode&quot;:&quot;222.830.810.457&quot;}">
                            <span aria-hidden="true">
                                <svg class="mr-4 card-img-top d-flex justify-content-center w-100 cardtop" width="32" height="29" viewBox="0 0 32 29" fill="none" alt="Detect my device automatically">
                                    <path d="M13.76 23.16H2.14V8.50005H25.68V10C26.4644 10.4782 27.178 11.0639 27.8 11.74V0.300049H0V25.2801H16C15.1377 24.7066 14.38 23.9895 13.76 23.16ZM2.14 2.50005H25.68V6.50005H2.14V2.50005Z" fill="#3176C8"></path>
                                    <path d="M27.8 23L26.7 21.9C27.217 21.1926 27.5907 20.3909 27.8 19.5401C27.9376 18.9772 28.0048 18.3995 28 17.82C27.9832 16.838 27.7651 15.8698 27.3592 14.9753C26.9533 14.0809 26.3681 13.2793 25.64 12.62C24.957 11.9699 24.1487 11.4657 23.2645 11.1383C22.3802 10.8108 21.4384 10.6671 20.4967 10.7157C19.555 10.7644 18.6331 11.0044 17.7872 11.4212C16.9414 11.838 16.1894 12.4228 15.577 13.1399C14.9647 13.857 14.5049 14.6913 14.2258 15.592C13.9467 16.4927 13.854 17.4409 13.9535 18.3786C14.0529 19.3163 14.3425 20.2239 14.8044 21.046C15.2663 21.868 15.8909 22.5874 16.64 23.16C17.8217 24.1618 19.3093 24.7313 20.8579 24.7749C22.4065 24.8186 23.9237 24.3337 25.16 23.4L30.46 28.7001L31.96 27.18L27.76 23H27.8ZM25.68 19.26C25.3356 20.3651 24.6067 21.3101 23.6253 21.9238C22.6439 22.5374 21.4751 22.7791 20.3309 22.6049C19.1866 22.4308 18.1427 21.8523 17.3883 20.9745C16.634 20.0966 16.2192 18.9775 16.2192 17.82C16.2192 16.6626 16.634 15.5435 17.3883 14.6656C18.1427 13.7878 19.1866 13.2093 20.3309 13.0352C21.4751 12.861 22.6439 13.1027 23.6253 13.7163C24.6067 14.33 25.3356 15.275 25.68 16.38C26 17.3134 26 18.3267 25.68 19.26Z" fill="#3176C8"></path>
                                </svg>
                            </span>
                            <span>
                                <button id="show-1" class="text-center cardtext" type="button" style="border: none; background: none;" id="btnDetectPC" aria-label="Detect my device automatically" tabindex="0">Detect my device automatically</button>
                            </span>
                        </div>
                    </div>
                    <div class="col-sm device-lg-column">
                        <div class="card-design h-100 pointcursor" id="browseallprod" data-metrics="{&quot;btnname&quot;:&quot;choosemymodel&quot;,&quot;appcode&quot;:&quot;222.830.810.133&quot;}" data-backdrop="static" data-toggle="modal" data-target="#chooseMyModal">
                            <span aria-hidden="true">
                                <svg class="mr-4 card-img-top d-flex justify-content-center w-100 cardtop" width="32" height="29" viewBox="0 0 30 25" fill="none" alt="Choose my model">
                                    <path d="M26.9577 14.738V0.238037H3.04171V14.738L0.02771 19.506V24.762H29.9717V19.506L26.9577 14.738ZM24.9577 2.24004V13.792H5.04171V2.24004H24.9577ZM4.74171 15.79H25.2557L27.1677 18.814H2.82971L4.74171 15.79ZM2.02771 20.816H11.2497V22.764H2.02771V20.816ZM18.8397 22.762V20.816H27.9697V22.764H18.8397V22.762Z" fill="#006BBD"></path>
                                </svg>
                            </span>
                            <span>
                                <button class="text-center cardtext" id="btnChooseProduct" type="button" style="border: none; background: none;" aria-label="Choose my model" tabindex="0">Choose my model</button>
                            </span>
                        </div>
                    </div>
                <div class="col-sm device-lg-column">
                    <div class="card-design h-100 pointcursor" id="contactusServiceTag" data-metrics="">
                        <span aria-hidden="true">
                            <svg class="mr-4 card-img-top d-flex justify-content-center w-100 cardtop" width="33" height="29" viewBox="0 0 30 31" fill="none" alt="Enter Service Tag/Product ID">
                                <path d="M14.5998 0.5H4.19976L-0.000244141 4.69995V15.1L15.3998 30.5L29.9998 15.8999L14.5998 0.5ZM1.99976 14.2999V5.5L4.99976 2.5H13.7998L27.1998 15.8999L15.1998 27.7L1.99976 14.2999Z" fill="#006BBD"></path>
                                <path d="M4.79976 5.50005C4.19976 6.10005 4.19976 7.1 4.79976 7.7C5.39976 8.3 6.39976 8.3 6.99976 7.7C7.59976 7.1 7.59976 6.10005 6.99976 5.50005C6.39976 4.90005 5.39976 4.90005 4.79976 5.50005Z" fill="#006BBD"></path>
                            </svg>
                        </span>
    
                        <div class="cardtext">
                            <span>
                                <button class="d-inline-block pr-4 text-center mb-0 " id="btnServiceTagEnter" type="button" style="border: none; background: none;" aria-label="Enter Service Tag/Product ID" tabindex="0">
                                    Enter Service Tag/Product ID
                                </button>
                            </span>
                            <span>
                                <a aria-label="tooltip" role="tooltip" tabindex="0" data-metrics="{&quot;btnname&quot;:&quot;info&quot;,&quot;appcode&quot;:&quot;222.830.810.449&quot;}" class="btn p-0 showmeProdIdentifier" data-backdrop="static" data-toggle="modal" data-target="#prodidentifierpopup-1">
                                    <span>
                                        <svg width="16" height="15" viewBox="0 0 16 15" fill="none" class="prodidentifiersvg" alt="tooltip" aria-label="title">
                                            <title id="title">How to find your product identifier</title>
                                            <path d="M8.00015 0.000732422C3.85845 0.000732422 0.500854 3.35823 0.500854 7.49993C0.500854 11.6416 3.85835 14.9991 8.00015 14.9991C12.1419 14.9991 15.4994 11.6416 15.4994 7.49993C15.4994 3.35823 12.1419 0.000732422 8.00015 0.000732422ZM8.00015 13.9991C4.41645 13.9991 1.50085 11.0836 1.50085 7.49993C1.50085 3.91623 4.41655 1.00073 8.00015 1.00073C11.5838 1.00073 14.4994 3.91623 14.4994 7.49993C14.4994 11.0836 11.5839 13.9991 8.00015 13.9991Z" fill="#006BBD"></path>
                                            <path d="M9.91105 3.63003C9.67915 3.43813 9.40125 3.29023 9.07705 3.18623C8.75325 3.08223 8.39495 3.02993 8.00325 3.02993C7.55505 3.02993 7.16485 3.09393 6.83335 3.22183C6.50135 3.35023 6.22745 3.52993 6.01115 3.76193C5.79525 3.99433 5.63315 4.27213 5.52525 4.59583C5.41735 4.92013 5.33275 5.39163 5.36315 5.79023H6.56505C6.53855 5.30623 6.66685 4.81023 6.87535 4.52993C7.08335 4.25013 7.45885 4.11003 8.00325 4.11003C8.27525 4.11003 8.50325 4.14423 8.68735 4.21213C8.87095 4.28003 9.01885 4.36983 9.13115 4.48213C9.24305 4.59393 9.32315 4.72183 9.37095 4.86593C9.41935 5.00993 9.44325 5.15793 9.44325 5.30973C9.44325 5.52603 9.41295 5.71203 9.35345 5.86783C9.29335 6.02413 9.21135 6.16813 9.10735 6.29993C9.00335 6.43173 8.87735 6.56213 8.72945 6.69003C8.58095 6.81803 8.41935 6.95863 8.24305 7.11003C8.05895 7.26243 7.90716 7.40793 7.78695 7.54853C7.66736 7.68813 7.56925 7.83663 7.49305 7.99183C7.41685 8.14813 7.36315 8.32003 7.33145 8.50843C7.29915 8.69593 7.28465 9.02993 7.28465 9.27023H8.48135C8.48135 9.09443 8.49885 8.82003 8.53105 8.68823C8.56285 8.55633 8.61705 8.43423 8.69325 8.32193C8.76895 8.21063 8.86705 8.09833 8.98715 7.98603C9.10725 7.87473 9.25915 7.74193 9.44325 7.59053C9.61905 7.43823 9.78115 7.29073 9.92905 7.14623C10.077 7.00263 10.203 6.84443 10.307 6.67263C10.411 6.50023 10.493 6.30593 10.5531 6.09013C10.6132 5.87433 10.6434 5.61403 10.6434 5.30983C10.6434 4.94993 10.5789 4.62823 10.451 4.34403C10.3232 4.06023 10.143 3.82193 9.91105 3.63003Z" fill="#006BBD"></path>
                                            <path d="M8.48305 10.7702H7.28335V11.9699H8.48305V10.7702Z" fill="#006BBD"></path>
                                        </svg>
                                    </span>
                                </a>
                            </span>
                        </div>
                    </div>
                </div>
                </div>
                <div class="row" id="step-1">
                    <h3 class="h3 text-center mt-4">Identify your device</h3>
                    <p class="text-center">Enter a Service Tag, Product ID, or Agrement ID</p>
                    <div class="col-3 col-sm-3 col-md-3 col-lg-3 col-xl-3" style="margin-left: 35%; padding-right: 0px;">
                        <input id="myInput" type="text" class="form-control" id="agrementtext">    
                    </div>
                    <div class="col-2 col-sm-2 col-md-2 col-lg-2 col-xl-2 ml-0" >
                        <button id="show-2" type="submit" class="btn btn-primary mb-3">submit</button>
                    </div>
                </div>
                <div class="row" id="step-2">
                    <h3 class="h3 text-center mt-4">This is the device you selected </h3>
                    <p class="text-center">Latitude 5520</p>
                    <p class="text-center">Service Tag: <span id="resultContainer"></span></p>
                    <div class="col-2 col-sm-2 col-md-2 col-lg-2 col-xl-2 ml-0" style="margin-left: 47%; padding-right: 0px;" >
                        <button id="show-3" type="submit" class="btn btn-primary mb-3">Submit</button>
                    </div>
                </div>
                <div class="row" id="step-3">
                    <h3 class="h3 text-center mt-4">Select an issue</h3>
                    <div class="col-3 col-sm-3 col-md-3 col-lg-3 col-xl-3" style="margin-left: 35%; padding-right: 0px;">
                        <select  class="form-select" aria-label="Default select example">
                            <option selected>Select an issue</option>
                            <option value="1">Startup & Power</option>
                            <option value="2">Hard Drive & RAID Controllers </option>
                            <option value="3">iDRAC, CMC, LifeCycle Controller</option>
                            <option value="4">Operating system</option>
                            <option value="5">Processor & Memory</option>
                            <option value="7">Storage</option>
                            <option value="8">Networking</option>
                            <option value="9">Software</option>
                            <option value="10">Status Updates</option>
                        </select>
                    </div>

                    <hr class="h-hr mt-4" aria-hidden="true">
                    <div class="col-12 col-sm-12 col-md-12 col-lg-12 col-xl-12 ml-0 text-center" >
                        <button id="showChat" type="submit" class="btn btn-primary mb-3" onclick='initEmbeddedMessaging()'>Start Chat</button>
                    </div>
                   
                </div>
            
                <!-- <div id="chatPopUp">
                    <div id="chatHeader">chat
                        <button id="close">X</button>
                    </div>
                    <div id="chatBody"></div>
                </div> -->
        </div>
    </div>

    
    <script type='text/javascript'>
        function initEmbeddedMessaging() {
            console.log('initEmbeddedMessaging clicked')
            
            try {
                embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US' add -pt_BR
    
                embeddedservice_bootstrap.init(
                    '00D8B0000004cZ5',
                    'MIAWPOC',
                    'https://dellservices--ge4.sandbox.my.site.com/ESWMIAWPOC1715760511897',
                    {
                        scrt2URL: 'https://dellservices--ge4.sandbox.my.salesforce-scrt.com'
                    }
                );
            } catch (err) {
                console.error('Error loading Embedded Messaging: ', err);
            }
        };
             var sIssue = "Account_Access";
             var sServiceTag = "DLPV0F3";
              var sQueueNameFromeSupport = "00G2R0000048staUAA";
        window.addEventListener("onEmbeddedMessagingReady", e => {
            console.log("onEmbeddedMessagingReady event triggered");
    
            embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields({
                "IssueType" : sIssue,
                "Service_Tag" : sServiceTag,
                "QueueNameFromeSupport" : sQueueNameFromeSupport
                
            });
        });
    
    </script>
    
    <!-- Optional JavaScript; choose one of the two! -->
    <script type='text/javascript' src='https://dellservices--ge4.sandbox.my.site.com/ESWMIAWPOC1715760511897/assets/js/bootstrap.min.js' ></script>
    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    -->

    
  </body>
</html>
