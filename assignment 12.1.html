<!-- Zyriyah Stoker -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Something fun</title>
    <style>
        body {
            background: linear-gradient(to bottom right,#FF1493 , #000);
            color: #fff;
            font-family: "Helvetica Neue", Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        header {
            padding: 20px;
        }
        h1 {
            font-size: 36px;
            margin-bottom: 30px;
        }
        .photo-container {
            position: relative;
            display: flex;
            justify-content: space-around;
            padding: 20px;
        }
        .photo {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 50%;
            border: 3px solid #fff;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.3);
            position: absolute;
            cursor: grab;
            user-drag: none;
            user-select: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>New webpage wooo</h1>
    </header>
    <div class="photo-container">
        <img class="photo" src="duck man.jpg" alt="Photo 1" draggable="true">
        <img class="photo" src="jake da dog.jpg" alt="Photo 2" draggable="true">
        <img class="photo" src="pit bull.jpg" alt="Photo 3" draggable="true">
    </div>

    <script>
        // JavaScript code here

        // Function to move photos around the screen
        function movePhotos() {
            const photos = document.querySelectorAll('.photo');

            function move() {
                photos.forEach(photo => {
                    // Get current position of the photo
                    let left = parseFloat(photo.style.left) || 0;
                    let top = parseFloat(photo.style.top) || 0;

                    // Calculate new position
                    const speedX = Math.random() * 4 - 2; // Random horizontal speed between -2 and 2
                    const speedY = Math.random() * 4 - 2; // Random vertical speed between -2 and 2
                    left += speedX;
                    top += speedY;

                    // Apply new position to the photo
                    photo.style.left = `${left}px`;
                    photo.style.top = `${top}px`;

                    // Wrap the photo around the screen if it goes beyond the edges
                    const screenWidth = window.innerWidth;
                    const screenHeight = window.innerHeight;
                    if (left > screenWidth) {
                        photo.style.left = `${-photo.width}px`;
                    } else if (left + photo.width < 0) {
                        photo.style.left = `${screenWidth}px`;
                    }
                    if (top > screenHeight) {
                        photo.style.top = `${-photo.height}px`;
                    } else if (top + photo.height < 0) {
                        photo.style.top = `${screenHeight}px`;
                    }
                });
                requestAnimationFrame(move);
            }

            move();
        }

        // Call the movePhotos function
        movePhotos();

        // Drag and Drop functionality
        let draggedPhoto = null;

        document.addEventListener('dragstart', (event) => {
            draggedPhoto = event.target;
            event.dataTransfer.setData('text/plain', ''); // Required for Firefox
        });

        document.addEventListener('dragend', () => {
            draggedPhoto = null;
        });

        document.addEventListener('dragover', (event) => {
            event.preventDefault();
        });

        document.addEventListener('drop', (event) => {
            event.preventDefault();
            if (draggedPhoto) {
                const offsetX = event.clientX - (draggedPhoto.width / 2);
                const offsetY = event.clientY - (draggedPhoto.height / 2);
                draggedPhoto.style.left = `${offsetX}px`;
                draggedPhoto.style.top = `${offsetY}px`;
            }
        });


    </script>
</body>
</html>
