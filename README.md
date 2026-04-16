# ZydecoMadness

body{
    background-color: purple;
    font-style: normal;
    font-size: large;
    color:yellow
}
.green{
    background-color: green;
}


const ZYDECO_VIDEO_URL = "https://youtu.be/mgv8tQ-15MA";
const VIDEO_ID = "mgv8tQ-15MA";
function embedZydecoVideo(containerId) {
    const container = document.getElementById(containerId);
    container.innerHTML = `
        <iframe 
            width="560" 
            height="315" 
            src="https://www.youtube.com/embed/${VIDEO_ID}" 
            title="YouTube video player" 
            frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
        </iframe>`;


}

const ZYDECO_VIDEO_URL = "https://youtu.be/mgv8tQ-15MA";
const VIDEO_ID = "mgv8tQ-15MA";
function embedZydecoVideo(containerId) {
    const container = document.getElementById(containerId);
    container.innerHTML = `
        <iframe 
            width="560" 
            height="315" 
            src="https://www.youtube.com/embed/${VIDEO_ID}" 
            title="YouTube video player" 
            frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
        </iframe>`;
}