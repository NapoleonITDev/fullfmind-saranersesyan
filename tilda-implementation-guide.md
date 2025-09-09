# Tilda Implementation Guide for Beat Your Brain Sales Email

## Overview
This guide provides step-by-step instructions for creating a high-converting sales email in Tilda for the "Beat Your Brain: Rhythmic Neuro Games" course.

## UTM Parameters Used
All buttons include UTM tracking for analytics:
- `utm_source=email`
- `utm_medium=newsletter` 
- `utm_campaign=brain_games_sale`
- `utm_content=[button_location]` (hero_cta, final_cta, learn_more)

## Tilda Block Structure

### 1. Hero Section (Tilda Block: Hero)
- **Background**: Gradient or brain-themed image
- **Elements**:
  - Main headline: "🧠 Beat Your Brain"
  - Subtitle: "Activate Your Brain Power with Rhythmic Neuro Games"
  - Urgency banner: "⏰ 90% OFF - Only $19 (Was $190) - Sale Ends in 2 Hours!"
  - Primary CTA button: "🚀 GET INSTANT ACCESS NOW"

### 2. Problem Section (Tilda Block: Text + Background)
- **Background**: Light yellow (#fff3cd)
- **Border**: Left border in warning color (#ffc107)
- **Content**: List of pain points with ❌ icons
- **Typography**: Bold headlines, readable body text

### 3. Solution Section (Tilda Block: Text + Background)
- **Background**: Light green (#d4edda)
- **Border**: Left border in success color (#28a745)
- **Content**: Benefits list with ✅ icons
- **Typography**: Emphasize the solution and benefits

### 4. Testimonials Section (Tilda Block: Cards/Grid)
- **Layout**: 3-column grid (responsive)
- **Cards**: White background with shadow
- **Elements**: Star ratings, testimonial text, author names
- **Colors**: Gold stars (#ffc107), blue author names (#667eea)

### 5. Course Details Section (Tilda Block: Grid)
- **Layout**: 4-column grid (responsive)
- **Icons**: Large emoji icons (📚, ⏰, 🎯, 🧠)
- **Content**: Course features and benefits
- **Colors**: Blue headings (#667eea)

### 6. Guarantee Section (Tilda Block: Text + Background)
- **Background**: Light green (#e8f5e8)
- **Border**: Green border (#28a745)
- **Content**: 14-day money-back guarantee
- **Typography**: Centered, bold

### 7. Final CTA Section (Tilda Block: Hero/Text)
- **Background**: Gradient (purple to blue)
- **Elements**:
  - Compelling headline
  - Social proof (16,843+ students)
  - Price display with strikethrough
  - Discount badge
  - Primary CTA button
  - Secondary "Learn More" button
  - Urgency message

### 8. Footer (Tilda Block: Text)
- **Background**: Dark (#333)
- **Content**: Contact info, unsubscribe links
- **Typography**: Small, muted text

## Color Scheme
- **Primary**: #667eea (Blue)
- **Secondary**: #764ba2 (Purple)
- **Accent**: #ff6b6b (Red/Orange)
- **Success**: #28a745 (Green)
- **Warning**: #ffc107 (Yellow)
- **Text**: #333 (Dark Gray)
- **Background**: #f8f9fa (Light Gray)

## Typography
- **Headlines**: Inter, 32-48px, Bold (700)
- **Subheadings**: Inter, 24-28px, Semi-bold (600)
- **Body**: Inter, 16-18px, Regular (400)
- **Buttons**: Inter, 18-28px, Bold (700)

## Mobile Responsiveness
- Use Tilda's responsive grid system
- Stack columns on mobile devices
- Adjust font sizes for mobile (reduce by 20-30%)
- Ensure buttons are touch-friendly (minimum 44px height)

## Implementation Steps

1. **Create New Tilda Page**
   - Choose "Blank Page" template
   - Set page title: "Beat Your Brain - Activate Your Brain Power"

2. **Add Hero Section**
   - Use "Hero" block
   - Add background image or gradient
   - Insert text elements and CTA button
   - Configure UTM parameters

3. **Add Problem Section**
   - Use "Text" block with background
   - Add custom CSS for left border
   - Create bullet list with icons

4. **Add Solution Section**
   - Similar to problem section
   - Use green color scheme
   - Add benefits list

5. **Add Testimonials**
   - Use "Cards" or "Grid" block
   - Create individual testimonial cards
   - Add star ratings and author info

6. **Add Course Details**
   - Use "Grid" block
   - Add icons and descriptions
   - Ensure responsive layout

7. **Add Guarantee**
   - Use "Text" block with background
   - Center align content
   - Add green styling

8. **Add Final CTA**
   - Use "Hero" or "Text" block
   - Add gradient background
   - Include all CTA elements

9. **Add Footer**
   - Use "Text" block
   - Add dark background
   - Include contact and legal info

10. **Test and Optimize**
    - Test on mobile devices
    - Check all UTM links
    - Verify email client compatibility
    - Test loading speed

## UTM Link Examples

### Primary CTA Button
```
https://newmindstart.com/beat-your-brain-rhythmic-neuro-games?utm_source=email&utm_medium=newsletter&utm_campaign=brain_games_sale&utm_content=hero_cta
```

### Learn More Button
```
https://newmindstart.com/beat-your-brain-rhythmic-neuro-games?utm_source=email&utm_medium=newsletter&utm_campaign=brain_games_sale&utm_content=learn_more
```

### Final CTA Button
```
https://newmindstart.com/beat-your-brain-rhythmic-neuro-games?utm_source=email&utm_medium=newsletter&utm_campaign=brain_games_sale&utm_content=final_cta
```

## Email Client Compatibility
- Use inline CSS for better compatibility
- Avoid complex layouts that might break
- Test in major email clients (Gmail, Outlook, Apple Mail)
- Use web-safe fonts as fallbacks

## Performance Optimization
- Optimize images (WebP format, proper sizing)
- Minimize CSS and JavaScript
- Use Tilda's built-in optimization features
- Enable compression and caching

## A/B Testing Recommendations
- Test different headlines
- Test button colors and text
- Test urgency messaging
- Test social proof numbers
- Test price presentation

## Analytics Setup
- Set up Google Analytics with UTM tracking
- Track conversion rates by UTM content
- Monitor email open rates and click-through rates
- Set up conversion goals in GA4
