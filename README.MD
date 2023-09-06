# Font Integration in CSS

Modern integration of locally installed fonts into CSS.

## Normal

    @font-face {
        font-family: 'Rubik';
        font-display: swap;
        font-style: normal;
        font-weight: normal;
        src: url('rubik-regular.woff2') format('woff2'),
            url('rubik-regular.woff') format('woff');
    }

## Italic

    @font-face {
        font-family: 'Rubik';
        font-display: swap;
        font-style: italic;
        font-weight: normal;
        src: url('rubik-italic.woff2') format('woff2'),
            url('rubik-italic.woff') format('woff');
    }

## Bold

    @font-face {
        font-family: 'Rubik';
        font-display: swap;
        font-style: normal;
        font-weight: bold;
        src: url('rubik-bold.woff2') format('woff2'),
            url('rubik-bold.woff') format('woff');
    }

## Usage

    body {
        font-family: 'Rubik', sans-serif;
    }

    h2 {
        font-weight: bold;
    }
