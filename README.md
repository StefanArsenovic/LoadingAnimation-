# LoadingAnimation-
<!DOCTYPE html>
<html>
    <head>
        <title>Loading Animation</title>
    </head>
    <body>
        <div class="loading">
        <div class="obj"></div>
        <div class="obj"></div>
        <div class="obj"></div>
        <div class="obj"></div>
        <div class="obj"></div>
        <div class="obj"></div>
        <div class="obj"></div>
        <div class="obj"></div>
        <div class="obj"></div>
        
        <p class="loading-text">Loading...</p>

       <style type="text/css>
body {
    margin: 0;
    padding: 0;
    
    background: #2980b9;
}

p {
    font-size: 25px;
    margin-top: 55px;
    
    color: white;
    display: block;
    text-align: center;

    position: absolute;
    
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.loading {
    position: absolute;
    
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    
    height: 40px;
    
    display: flex;
    align-items: center;
}

.obj {
    width: 6px;
    height: 40px;
    
    background: white;
    
    margin: 0 3px;
    border-radius: 10px;
    
    animation: loading 0.8s infinite;
}

.obj:nth-child(2) {
    animation-delay: 0.1s;
}

.obj:nth-child(3) {
    animation-delay: 0.2s;
}

.obj:nth-child(4) {
    animation-delay: 0.3s;
}

.obj:nth-child(5) {
    animation-delay: 0.4s;
}

.obj:nth-child(6) {
    animation-delay: 0.5s;
}

.obj:nth-child(7) {
    animation-delay: 0.6s;
}

.obj:nth-child(8) {
    animation-delay: 0.7s;
}

.obj:nth-child(9) {
    animation-delay: 0.8s;
}

@keyframes loading {
    0% {
        height: 0;
    }
    50% {
        height: 40px;
    }
    100% {
        height: 0;
    }
}
        </div>
    </body>
</html>

