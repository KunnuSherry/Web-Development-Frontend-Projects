Instructions to run the file:
1. download the files of the directory with image too.
2. Create a live preview server from you VSCode settings.
3. Run and enjoy !

Design Choices:
Flexbox for Layout:

Flexbox was chosen to create a responsive and easy-to-manage layout. Flexbox simplifies the process of aligning items both horizontally and vertically, which is particularly useful for creating navigation bars and centering content within containers.
Centered Navigation Bar:

The navigation bar was centered within the .main container using justify-content: center and align-items: center. This ensures that the navigation bar remains centrally aligned regardless of the viewport size.
Responsive Width:

The width of the .nav element was set to 70vw, making it responsive to different screen sizes. This ensures the navigation bar adapts to various device widths while maintaining a proportionate size.
Z-Index for Layering:

The z-index property was used to manage the stacking order of overlapping elements. This is essential in designs where elements like dropdowns or modals need to appear above other content.
Positioned Elements:

Elements were positioned using position: absolute to demonstrate the use of z-index and to create a layered layout where elements can overlap.

I havent used any libraries here.

Design Link for reference : https://www.figma.com/community/file/1145991068621514311/app-landing-page-finance-bank-money
