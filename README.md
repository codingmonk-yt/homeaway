# Homeaway Project by CodingMonk

## Tailwind Configuration

```js

const defaultTheme = require('tailwindcss/defaultTheme');

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ['./index.html', './src/**/*.{js,ts,jsx,tsx}'],
  darkMode: 'class',
  theme: {
    fontFamily: {
      satoshi: ['Inter', 'sans-serif'],
    },
    screens: {
      '2xsm': '375px',
      xsm: '425px',
      '3xl': '2000px',
      ...defaultTheme.screens,
    },
    extend: {
      colors: {
        current: 'currentColor',
        transparent: 'transparent',
        white: '#FFFFFF',
        black: '#1C2434',
        red: '#FB5454',
        'black-2': '#010101',
        body: '#64748B',
        bodydark: '#AEB7C0',
        bodydark1: '#DEE4EE',
        bodydark2: '#8A99AF',
        primary: '#3C50E0',
        secondary: '#80CAEE',
        stroke: '#E2E8F0',
        gray: '#EFF4FB',
        graydark: '#333A48',
        'gray-2': '#F7F9FC',
        'gray-3': '#FAFAFA',
        whiten: '#F1F5F9',
        whiter: '#F5F7FD',
        boxdark: '#24303F',
        'boxdark-2': '#1A222C',
        strokedark: '#2E3A47',
        'form-strokedark': '#3d4d60',
        'form-input': '#1d2a39',
        'meta-1': '#DC3545',
        'meta-2': '#EFF2F7',
        'meta-3': '#10B981',
        'meta-4': '#313D4A',
        'meta-5': '#259AE6',
        'meta-6': '#FFBA00',
        'meta-7': '#FF6766',
        'meta-8': '#F0950C',
        'meta-9': '#E5E7EB',
        'meta-10': '#0FADCF',
        success: '#219653',
        danger: '#D34053',
        warning: '#FFA70B',
      },
      fontSize: {
        'title-xxl': ['44px', '55px'],
        'title-xxl2': ['42px', '58px'],
        'title-xl': ['36px', '45px'],
        'title-xl2': ['33px', '45px'],
        'title-lg': ['28px', '35px'],
        'title-md': ['24px', '30px'],
        'title-md2': ['26px', '30px'],
        'title-sm': ['20px', '26px'],
        'title-sm2': ['22px', '28px'],
        'title-xsm': ['18px', '24px'],
      },
      spacing: {
        4.5: '1.125rem',
        5.5: '1.375rem',
        6.5: '1.625rem',
        7.5: '1.875rem',
        8.5: '2.125rem',
        9.5: '2.375rem',
        10.5: '2.625rem',
        11: '2.75rem',
        11.5: '2.875rem',
        12.5: '3.125rem',
        13: '3.25rem',
        13.5: '3.375rem',
        14: '3.5rem',
        14.5: '3.625rem',
        15: '3.75rem',
        15.5: '3.875rem',
        16: '4rem',
        16.5: '4.125rem',
        17: '4.25rem',
        17.5: '4.375rem',
        18: '4.5rem',
        18.5: '4.625rem',
        19: '4.75rem',
        19.5: '4.875rem',
        21: '5.25rem',
        21.5: '5.375rem',
        22: '5.5rem',
        22.5: '5.625rem',
        24.5: '6.125rem',
        25: '6.25rem',
        25.5: '6.375rem',
        26: '6.5rem',
        27: '6.75rem',
        27.5: '6.875rem',
        29: '7.25rem',
        29.5: '7.375rem',
        30: '7.5rem',
        31: '7.75rem',
        32.5: '8.125rem',
        33: '8.25rem',
        34: '8.5rem',
        34.5: '8.625rem',
        35: '8.75rem',
        36.5: '9.125rem',
        37.5: '9.375rem',
        39: '9.75rem',
        39.5: '9.875rem',
        40: '10rem',
        42.5: '10.625rem',
        44: '11rem',
        45: '11.25rem',
        46: '11.5rem',
        47.5: '11.875rem',
        49: '12.25rem',
        50: '12.5rem',
        52: '13rem',
        52.5: '13.125rem',
        54: '13.5rem',
        54.5: '13.625rem',
        55: '13.75rem',
        55.5: '13.875rem',
        59: '14.75rem',
        60: '15rem',
        62.5: '15.625rem',
        65: '16.25rem',
        67: '16.75rem',
        67.5: '16.875rem',
        70: '17.5rem',
        72.5: '18.125rem',
        73: '18.25rem',
        75: '18.75rem',
        90: '22.5rem',
        94: '23.5rem',
        95: '23.75rem',
        100: '25rem',
        115: '28.75rem',
        125: '31.25rem',
        132.5: '33.125rem',
        150: '37.5rem',
        171.5: '42.875rem',
        180: '45rem',
        187.5: '46.875rem',
        203: '50.75rem',
        230: '57.5rem',
        242.5: '60.625rem',
      },
      maxWidth: {
        2.5: '0.625rem',
        3: '0.75rem',
        4: '1rem',
        7: '1.75rem',
        9: '2.25rem',
        10: '2.5rem',
        10.5: '2.625rem',
        11: '2.75rem',
        13: '3.25rem',
        14: '3.5rem',
        15: '3.75rem',
        16: '4rem',
        22.5: '5.625rem',
        25: '6.25rem',
        30: '7.5rem',
        34: '8.5rem',
        35: '8.75rem',
        40: '10rem',
        42.5: '10.625rem',
        44: '11rem',
        45: '11.25rem',
        60: '15rem',
        70: '17.5rem',
        90: '22.5rem',
        94: '23.5rem',
        125: '31.25rem',
        132.5: '33.125rem',
        142.5: '35.625rem',
        150: '37.5rem',
        180: '45rem',
        203: '50.75rem',
        230: '57.5rem',
        242.5: '60.625rem',
        270: '67.5rem',
        280: '70rem',
        292.5: '73.125rem',
      },
      maxHeight: {
        35: '8.75rem',
        70: '17.5rem',
        90: '22.5rem',
        550: '34.375rem',
        300: '18.75rem',
      },
      minWidth: {
        22.5: '5.625rem',
        42.5: '10.625rem',
        47.5: '11.875rem',
        75: '18.75rem',
      },
      zIndex: {
        999999: '999999',
        99999: '99999',
        9999: '9999',
        999: '999',
        99: '99',
        9: '9',
        1: '1',
      },
      opacity: {
        65: '.65',
      },
      aspectRatio: {
        '4/3': '4 / 3',
        '21/9': '21 / 9',
      },
      backgroundImage: {
        video: "url('../images/video/video.png')",
      },
      content: {
        'icon-copy': 'url("../images/icon/icon-copy-alt.svg")',
      },
      transitionProperty: { width: 'width', stroke: 'stroke' },
      borderWidth: {
        6: '6px',
        10: '10px',
        12: '12px',
      },
      boxShadow: {
        default: '0px 8px 13px -3px rgba(0, 0, 0, 0.07)',
        card: '0px 1px 3px rgba(0, 0, 0, 0.12)',
        'card-2': '0px 1px 2px rgba(0, 0, 0, 0.05)',
        switcher:
          '0px 2px 4px rgba(0, 0, 0, 0.2), inset 0px 2px 2px #FFFFFF, inset 0px -1px 1px rgba(0, 0, 0, 0.1)',
        'switch-1': '0px 0px 5px rgba(0, 0, 0, 0.15)',
        1: '0px 1px 3px rgba(0, 0, 0, 0.08)',
        2: '0px 1px 4px rgba(0, 0, 0, 0.12)',
        3: '0px 1px 5px rgba(0, 0, 0, 0.14)',
        4: '0px 4px 10px rgba(0, 0, 0, 0.12)',
        5: '0px 1px 1px rgba(0, 0, 0, 0.15)',
        6: '0px 3px 15px rgba(0, 0, 0, 0.1)',
        7: '-5px 0 0 #313D4A, 5px 0 0 #313D4A',
        8: '1px 0 0 #313D4A, -1px 0 0 #313D4A, 0 1px 0 #313D4A, 0 -1px 0 #313D4A, 0 3px 13px rgb(0 0 0 / 8%)',
        9: '0px 2px 3px rgba(183, 183, 183, 0.5)',
        10: '0px 1px 2px 0px rgba(0, 0, 0, 0.10)',
        11: '0px 1px 3px 0px rgba(166, 175, 195, 0.40)',
        12: '0px 0.5px 3px 0px rgba(0, 0, 0, 0.18)',
        13: '0px 1px 3px 0px rgba(0, 0, 0, 0.08)',
        14: '0px 2px 3px 0px rgba(0, 0, 0, 0.10)',
      },
      dropShadow: {
        1: '0px 1px 0px #E2E8F0',
        2: '0px 1px 4px rgba(0, 0, 0, 0.12)',
        3: '0px 0px 4px rgba(0, 0, 0, 0.15)',
        4: '0px 0px 2px rgba(0, 0, 0, 0.2)',
        5: '0px 1px 5px rgba(0, 0, 0, 0.2)',
      },
      keyframes: {
        linspin: {
          '100%': { transform: 'rotate(360deg)' },
        },
        easespin: {
          '12.5%': { transform: 'rotate(135deg)' },
          '25%': { transform: 'rotate(270deg)' },
          '37.5%': { transform: 'rotate(405deg)' },
          '50%': { transform: 'rotate(540deg)' },
          '62.5%': { transform: 'rotate(675deg)' },
          '75%': { transform: 'rotate(810deg)' },
          '87.5%': { transform: 'rotate(945deg)' },
          '100%': { transform: 'rotate(1080deg)' },
        },
        'left-spin': {
          '0%': { transform: 'rotate(130deg)' },
          '50%': { transform: 'rotate(-5deg)' },
          '100%': { transform: 'rotate(130deg)' },
        },
        'right-spin': {
          '0%': { transform: 'rotate(-130deg)' },
          '50%': { transform: 'rotate(5deg)' },
          '100%': { transform: 'rotate(-130deg)' },
        },
        rotating: {
          '0%, 100%': { transform: 'rotate(360deg)' },
          '50%': { transform: 'rotate(0deg)' },
        },
        topbottom: {
          '0%, 100%': { transform: 'translate3d(0, -100%, 0)' },
          '50%': { transform: 'translate3d(0, 0, 0)' },
        },
        bottomtop: {
          '0%, 100%': { transform: 'translate3d(0, 0, 0)' },
          '50%': { transform: 'translate3d(0, -100%, 0)' },
        },
        line: {
          '0%, 100%': { transform: 'translateY(0)' },
          '50%': { transform: 'translateY(100%)' },
        },
        'line-revert': {
          '0%, 100%': { transform: 'translateY(100%)' },
          '50%': { transform: 'translateY(0)' },
        },
      },
      animation: {
        linspin: 'linspin 1568.2353ms linear infinite',
        easespin: 'easespin 5332ms cubic-bezier(0.4, 0, 0.2, 1) infinite both',
        'left-spin':
          'left-spin 1333ms cubic-bezier(0.4, 0, 0.2, 1) infinite both',
        'right-spin':
          'right-spin 1333ms cubic-bezier(0.4, 0, 0.2, 1) infinite both',
        'ping-once': 'ping 5s cubic-bezier(0, 0, 0.2, 1)',
        rotating: 'rotating 30s linear infinite',
        topbottom: 'topbottom 60s infinite alternate linear',
        bottomtop: 'bottomtop 60s infinite alternate linear',
        'spin-1.5': 'spin 1.5s linear infinite',
        'spin-2': 'spin 2s linear infinite',
        'spin-3': 'spin 3s linear infinite',
        line1: 'line 10s infinite linear',
        line2: 'line-revert 8s infinite linear',
        line3: 'line 7s infinite linear',
      },
    },
  },
  plugins: [],
};
```

## Global CSS

```css


@import url('https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap');

@tailwind base;
@tailwind components;
@tailwind utilities;


@layer base {
  body {
    @apply relative z-1 bg-whiten font-satoshi text-base font-normal text-body;
  }
}


@layer utilities {
  /* Chrome, Safari and Opera */
  .no-scrollbar::-webkit-scrollbar {
    display: none;
  }

  .no-scrollbar {
    -ms-overflow-style: none; /* IE and Edge */
    scrollbar-width: none; /* Firefox */
  }
}
```


### Flat picker instance

```js

flatpickr(".form-datepicker", {
      mode: "single",
      static: true,
      monthSelectorType: "static",
      dateFormat: "M j, Y",
      prevArrow:
        '<svg className="fill-current" width="7" height="11" viewBox="0 0 7 11"><path d="M5.4 10.8l1.4-1.4-4-4 4-4L5.4 0 0 5.4z" /></svg>',
      nextArrow:
        '<svg className="fill-current" width="7" height="11" viewBox="0 0 7 11"><path d="M1.4 10.8L0 9.4l4-4-4-4L1.4 0l5.4 5.4z" /></svg>',
    });

```

### CSS for Flat Picker

```css

.flatpickr-wrapper {
  @apply w-full;
}
.flatpickr-months .flatpickr-prev-month:hover svg,
.flatpickr-months .flatpickr-next-month:hover svg {
  @apply fill-primary;
}
.flatpickr-calendar.arrowTop:before {
  @apply dark:!border-b-boxdark;
}
.flatpickr-calendar.arrowTop:after {
  @apply dark:!border-b-boxdark;
}
.flatpickr-calendar {
  @apply !p-6 dark:!bg-boxdark dark:!text-bodydark dark:!shadow-8 2xsm:!w-auto;
}
.flatpickr-day {
  @apply dark:!text-bodydark dark:hover:!border-meta-4 dark:hover:!bg-meta-4;
}
.flatpickr-months .flatpickr-prev-month,
.flatpickr-months .flatpickr-next-month {
  @apply !top-7 dark:!fill-white dark:!text-white;
}
.flatpickr-months .flatpickr-prev-month.flatpickr-prev-month,
.flatpickr-months .flatpickr-next-month.flatpickr-prev-month {
  @apply !left-7;
}
.flatpickr-months .flatpickr-prev-month.flatpickr-next-month,
.flatpickr-months .flatpickr-next-month.flatpickr-next-month {
  @apply !right-7;
}
span.flatpickr-weekday,
.flatpickr-months .flatpickr-month {
  @apply dark:!fill-white dark:!text-white;
}
.flatpickr-day.inRange {
  @apply dark:!shadow-7;
  box-shadow: -5px 0 0 #EFF4FB, 5px 0 0 #EFF4FB;
}
.flatpickr-day.inRange,
.flatpickr-day.prevMonthDay.inRange,
.flatpickr-day.nextMonthDay.inRange,
.flatpickr-day.today.inRange,
.flatpickr-day.prevMonthDay.today.inRange,
.flatpickr-day.nextMonthDay.today.inRange,
.flatpickr-day:hover,
.flatpickr-day.prevMonthDay:hover,
.flatpickr-day.nextMonthDay:hover,
.flatpickr-day:focus,
.flatpickr-day.prevMonthDay:focus,
.flatpickr-day.nextMonthDay:focus {
  @apply border-gray bg-gray dark:!border-meta-4 dark:!bg-meta-4;
}
.flatpickr-day.selected,
.flatpickr-day.startRange,
.flatpickr-day.selected,
.flatpickr-day.endRange {
  @apply dark:!text-white;
}
.flatpickr-day.selected,
.flatpickr-day.startRange,
.flatpickr-day.endRange,
.flatpickr-day.selected.inRange,
.flatpickr-day.startRange.inRange,
.flatpickr-day.endRange.inRange,
.flatpickr-day.selected:focus,
.flatpickr-day.startRange:focus,
.flatpickr-day.endRange:focus,
.flatpickr-day.selected:hover,
.flatpickr-day.startRange:hover,
.flatpickr-day.endRange:hover,
.flatpickr-day.selected.prevMonthDay,
.flatpickr-day.startRange.prevMonthDay,
.flatpickr-day.endRange.prevMonthDay,
.flatpickr-day.selected.nextMonthDay,
.flatpickr-day.startRange.nextMonthDay,
.flatpickr-day.endRange.nextMonthDay {
  background: #3c50e0;
  @apply !border-primary !bg-primary hover:!border-primary hover:!bg-primary;
}
.flatpickr-day.selected.startRange + .endRange:not(:nth-child(7n + 1)),
.flatpickr-day.startRange.startRange + .endRange:not(:nth-child(7n + 1)),
.flatpickr-day.endRange.startRange + .endRange:not(:nth-child(7n + 1)) {
  box-shadow: -10px 0 0 #3c50e0;
}

```

### CATEGORY LIST

```js

const CATEGORY = [
  {
    key: 0,
    icon: <PiIsland size={20} />,
    label: "Islands",
  },
  {
    key: 1,
    icon: <FaRegSnowflake size={20} />,
    label: "Arctic",
  },
  {
    key: 2,
    icon: <PiFarm size={20} />,
    label: "Farms",
  },
  {
    key: 3,
    icon: <MdOutlinePool size={20} />,
    label: "Amazing pools",
  },
  {
    key: 4,
    icon: <GiTreehouse size={20} />,
    label: "Treehouses",
  },
  {
    key: 5,
    icon: <HiHomeModern size={20} />,
    label: "Luxe",
  },
  {
    key: 6,
    icon: <MdVilla size={20} />,
    label: "Mansions",
  },
  {
    key: 7,
    icon: <FaUmbrellaBeach size={20} />,
    label: "Beachfronts",
  },
  {
    key: 8,
    icon: <FaFireAlt size={20} />,
    label: "Trending",
  },
  {
    key: 9,
    icon: <PiIslandFill size={20} />,
    label: "Lakefront",
  },
  {
    key: 10,
    icon: <MdCabin size={20} />,
    label: "Cabins",
  },
  {
    key: 11,
    icon: <MdCastle size={20} />,
    label: "Castle",
  },
  {
    key: 12,
    icon: <GiMountainCave size={20} />,
    label: "Caves",
  },
  {
    key: 13,
    icon: <PiBarn size={20} />,
    label: "Barns",
  },
  {
    key: 14,
    icon: <PiCactusFill size={20} />,
    label: "Desert",
  },
  {
    key: 15,
    icon: <PiWindmill size={20} />,
    label: "Windmill",
  },
  {
    key: 16,
    icon: <GiGrapes size={20} />,
    label: "Wineyard",
  },
  {
    key: 17,
    icon: <GiCampingTent size={20} />,
    label: "Camping",
  },
  {
    key: 18,
    icon: <FaCity size={20} />,
    label: "Top Cities",
  },
];
```

### Simplebar

```js

import "simplebar-react/dist/simplebar.min.css";

```


### Dummy properties list

```js

const PROPERTIES = [
  {
    key: 0,
    imgSrc:
      "https://images.pexels.com/photos/7031407/pexels-photo-7031407.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Imereti, Georgia",
    rating: 4.9,
    price: 10731,
  },
  {
    key: 1,
    imgSrc:
      "https://images.pexels.com/photos/1542499/pexels-photo-1542499.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Santorini, Greece",
    rating: 4.8,
    price: 15250,
  },
  {
    key: 2,
    imgSrc:
      "https://images.pexels.com/photos/210557/pexels-photo-210557.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Malibu, California",
    rating: 4.9,
    price: 20350,
  },
  {
    key: 3,
    imgSrc:
      "https://images.pexels.com/photos/358574/pexels-photo-358574.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Bali, Indonesia",
    rating: 5.0,
    price: 11200,
  },
  {
    key: 4,
    imgSrc:
      "https://images.pexels.com/photos/241693/pexels-photo-241693.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Tuscany, Italy",
    rating: 4.7,
    price: 17500,
  },
  {
    key: 5,
    imgSrc:
      "https://images.pexels.com/photos/261146/pexels-photo-261146.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Capri, Italy",
    rating: 4.9,
    price: 18750,
  },
  {
    key: 6,
    imgSrc:
      "https://images.pexels.com/photos/221457/pexels-photo-221457.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Ibiza, Spain",
    rating: 4.8,
    price: 14100,
  },
  {
    key: 7,
    imgSrc:
      "https://images.pexels.com/photos/708764/pexels-photo-708764.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Crete, Greece",
    rating: 4.9,
    price: 16200,
  },
  {
    key: 8,
    imgSrc:
      "https://images.pexels.com/photos/259588/pexels-photo-259588.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Marrakech, Morocco",
    rating: 4.7,
    price: 11500,
  },
  {
    key: 9,
    imgSrc:
      "https://images.pexels.com/photos/1287075/pexels-photo-1287075.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Phuket, Thailand",
    rating: 5.0,
    price: 9500,
  },
  {
    key: 10,
    imgSrc:
      "https://images.pexels.com/photos/417321/pexels-photo-417321.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Santorini, Greece",
    rating: 4.9,
    price: 12850,
  },
  {
    key: 11,
    imgSrc:
      "https://images.pexels.com/photos/544968/pexels-photo-544968.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Majorca, Spain",
    rating: 4.8,
    price: 15400,
  },
  {
    key: 12,
    imgSrc:
      "https://images.pexels.com/photos/106399/pexels-photo-106399.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Mykonos, Greece",
    rating: 5.0,
    price: 13400,
  },
  {
    key: 13,
    imgSrc:
      "https://images.pexels.com/photos/221475/pexels-photo-221475.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Amalfi Coast, Italy",
    rating: 4.9,
    price: 16500,
  },
  {
    key: 14,
    imgSrc:
      "https://images.pexels.com/photos/415234/pexels-photo-415234.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Palma, Spain",
    rating: 4.8,
    price: 13800,
  },
  {
    key: 15,
    imgSrc:
      "https://images.pexels.com/photos/1842332/pexels-photo-1842332.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Bora Bora, French Polynesia",
    rating: 5.0,
    price: 20300,
  },
  {
    key: 16,
    imgSrc:
      "https://images.pexels.com/photos/7061662/pexels-photo-7061662.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Dubai, UAE",
    rating: 4.9,
    price: 22100,
  },
  {
    key: 17,
    imgSrc:
      "https://images.pexels.com/photos/7031595/pexels-photo-7031595.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Barbados, Caribbean",
    rating: 4.7,
    price: 16550,
  },
  {
    key: 18,
    imgSrc:
      "https://images.pexels.com/photos/258154/pexels-photo-258154.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Koh Samui, Thailand",
    rating: 5.0,
    price: 14250,
  },
  {
    key: 19,
    imgSrc:
      "https://images.pexels.com/photos/221528/pexels-photo-221528.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Hvar, Croatia",
    rating: 4.9,
    price: 17300,
  },
  {
    key: 20,
    imgSrc:
      "https://images.pexels.com/photos/258192/pexels-photo-258192.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Corfu, Greece",
    rating: 4.8,
    price: 13400,
  },
  {
    key: 21,
    imgSrc:
      "https://images.pexels.com/photos/325826/pexels-photo-325826.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Zanzibar, Tanzania",
    rating: 5.0,
    price: 16250,
  },
  {
    key: 22,
    imgSrc:
      "https://images.pexels.com/photos/1778123/pexels-photo-1778123.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Bahamas, Caribbean",
    rating: 4.9,
    price: 19800,
  },
  {
    key: 23,
    imgSrc:
      "https://images.pexels.com/photos/1144176/pexels-photo-1144176.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Puerto Rico, USA",
    rating: 4.7,
    price: 14450,
  },
  {
    key: 24,
    imgSrc:
      "https://images.pexels.com/photos/1382615/pexels-photo-1382615.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Cyprus, Europe",
    rating: 4.9,
    price: 12250,
  },
  {
    key: 25,
    imgSrc:
      "https://images.pexels.com/photos/274174/pexels-photo-274174.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Goa, India",
    rating: 5.0,
    price: 11500,
  },
  {
    key: 26,
    imgSrc:
      "https://images.pexels.com/photos/1408662/pexels-photo-1408662.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Hawaii, USA",
    rating: 4.8,
    price: 21500,
  },
  {
    key: 27,
    imgSrc:
      "https://images.pexels.com/photos/1872200/pexels-photo-1872200.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Malé, Maldives",
    rating: 5.0,
    price: 20900,
  },
  {
    key: 28,
    imgSrc:
      "https://images.pexels.com/photos/210196/pexels-photo-210196.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Langkawi, Malaysia",
    rating: 4.7,
    price: 18250,
  },
  {
    key: 29,
    imgSrc:
      "https://images.pexels.com/photos/273263/pexels-photo-273263.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1",
    name: "Seychelles, Africa",
    rating: 4.9,
    price: 20100,
  },
];

```
