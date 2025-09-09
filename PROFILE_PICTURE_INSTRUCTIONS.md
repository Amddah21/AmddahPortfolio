# How to Add Your Profile Picture

## Step 1: Save Your Profile Picture

1. Save your profile picture as `profile.jpg` in the `public/` folder
2. Make sure the image is:
   - Square aspect ratio (1:1) for best results
   - High quality (at least 400x400 pixels)
   - JPG format (or convert to JPG)

## Step 2: File Location

Your profile picture should be saved at:
```
portfolio/public/profile.jpg
```

## Step 3: Alternative Formats

If you prefer a different format, you can also use:
- `profile.png`
- `profile.webp`
- `profile.jpeg`

Just update the file path in the components if you use a different format.

## Step 4: Test the Changes

1. Start the development server:
   ```bash
   npm run dev
   ```

2. Open [http://localhost:3000](http://localhost:3000) to see your profile picture

## Image Optimization Tips

- **Size**: Keep the file size under 500KB for faster loading
- **Format**: JPG is recommended for photos
- **Dimensions**: Square images work best (e.g., 400x400, 500x500, 600x600)
- **Quality**: Use high quality but optimize for web

## Troubleshooting

If your image doesn't appear:
1. Check the file path is correct
2. Make sure the file is in the `public/` folder
3. Verify the filename matches exactly (case-sensitive)
4. Check the browser console for any errors

Your profile picture will now appear in:
- Hero section (main landing area)
- About section (larger version)
