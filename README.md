# MDN contributor spotlight

Content for the contributor spotlight on MDN Web Docs.

## Profile images

- Aspect ratio 1×1
- Dimensions 400×400 pixels
- Format JPEG

To resize and optimize a square image, you can use [Squoosh](https://squoosh.app/) right in your browser:

- Check the Resize option, set it to 400×400.
- Choose the MozJPEG format and set the quality to 75.

### Testing Contributor Spotlight Pages Locally

To test the Contributor Spotlight pages on your local setup:

1. Make sure you have a fork of both repositories:

   - [`mdn/content`](https://github.com/mdn/content)
   - [`mdn-contributor-spotlight`](https://github.com/mdn/mdn-contributor-spotlight)

2. Clone both repositories into the same parent folder so your structure looks like this:

   ```
   ./content
   ./mdn-contributor-spotlight
   ```

3. In the `content` directory, run:

   ```
   cd content
   echo "CONTRIBUTOR_SPOTLIGHT_ROOT=../mdn-contributor-spotlight/contributors" >> .env
   ```

4. Install dependencies and start the local server

   ```
   yarn && yarn start
   ```

Your local instance should now include the Contributor Spotlight pages.
