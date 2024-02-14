# foto2.collage {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* Adjust the number of columns as needed */
    gap: 10px; /* Adjust the gap between images */
}

.collage img {
    width: 100%;
    height: auto;
    object-fit: cover; /* Ensure images maintain their aspect ratio */
}
