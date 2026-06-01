# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
import { CheckCircle2 } from 'lucide-react';
import { Button } from './ui/button';
import logo from 'figma:asset/0b30f62e93f9bbd861fdc65d629f464b8af4bc1d.png';

interface ThankYouScreenProps {
  onBackToHome: () => void;
}

export function ThankYouScreen({ onBackToHome }: ThankYouScreenProps) {
  return (
    <div className="relative bg-gradient-to-b from-sky-200 via-sky-100 to-orange-100 rounded-3xl overflow-hidden shadow-2xl border-8 border-black h-full flex flex-col">
      {/* Sports Background Image */}
      <div 
        className="absolute inset-0 opacity-15 bg-cover bg-center"
        style={{ backgroundImage: `url(https://images.unsplash.com/photo-1699134710640-c2b282ba8e11?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHxydW5uaW5nJTIwdHJhY2slMjBhdGhsZXRpY3N8ZW58MXx8fHwxNzYyNjI3ODA2fDA&ixlib=rb-4.1.0&q=80&w=1080&utm_source=figma&utm_medium=referral)` }}
      ></div>

      {/* Header */}
      <div className="relative z-10 bg-blue-600/95 backdrop-blur-sm text-white p-3 flex items-center justify-center">
        <img src={logo} alt="Saveetha Engineering College" className="h-10 object-contain" />
      </div>

      {/* Content */}
      <div className="flex-1 flex flex-col items-center justify-center p-8 relative z-10">
        {/* Decorative triangles */}
        <div className="absolute top-12 right-8 w-0 h-0 border-l-[20px] border-l-transparent border-r-[20px] border-r-transparent border-b-[35px] border-b-purple-400/50"></div>
        <div className="absolute top-24 right-16 w-0 h-0 border-l-[15px] border-l-transparent border-r-[15px] border-r-transparent border-b-[25px] border-b-orange-400/50"></div>
        <div className="absolute bottom-32 left-8 w-0 h-0 border-l-[18px] border-l-transparent border-r-[18px] border-r-transparent border-b-[30px] border-b-yellow-400/50"></div>

        {/* Success Icon */}
        <div className="mb-6">
          <CheckCircle2 className="w-24 h-24 text-green-500" />
        </div>

        {/* Thank You Message */}
        <h1 className="text-teal-600 text-center mb-4">
          THANK YOU
        </h1>
        
        <p className="text-center text-gray-700 max-w-xs mb-8">
          We are all eagerly waiting for your participation in the sports events
        </p>

        {/* Back to Home Button */}
        <Button 
          onClick={onBackToHome}
          className="bg-teal-500 hover:bg-teal-600 text-white px-8 py-6 rounded-xl shadow-lg"
        >
          Back to Home
        </Button>
      </div>

      {/* Footer with sports silhouettes */}
      <div className="relative h-40 z-10">
        <div className="absolute bottom-0 left-0 right-0">
          {/* Stadium/court gradient background */}
          <div className="h-32 bg-gradient-to-t from-orange-500 via-orange-400 to-transparent opacity-80"></div>
          
          {/* Athlete silhouettes */}
          <div className="absolute bottom-8 left-12 flex gap-8">
            {/* Basketball player */}
            <div className="relative">
              <div className="w-16 h-24 bg-black rounded-t-full opacity-90"></div>
              <div className="absolute -top-4 left-6 w-6 h-6 bg-orange-600 rounded-full"></div>
            </div>
            
            {/* Runner */}
            <div className="w-20 h-20 bg-black rounded-t-full opacity-90 mt-4"></div>
          </div>

          {/* Trophy/medal illustration */}
          <div className="absolute bottom-12 right-12">
            <div className="w-16 h-20 bg-gradient-to-b from-yellow-400 to-yellow-600 rounded-lg opacity-90"></div>
            <div className="absolute -top-2 left-4 w-8 h-8 bg-yellow-500 rounded-full"></div>
          </div>
        </div>
        
        <div className="absolute bottom-4 left-0 right-0 text-center text-teal-600 text-xs">
          Contact us:<br />
          sports@saveetha.ac.in
        </div>
      </div>
    </div>
  );
}

```
## OUTPUT:
![alt text](<Screenshot 2025-11-09 165204.png>)
![alt text](<Screenshot 2025-11-09 172251.png>)

![alt text](<Screenshot 2025-11-09 165339.png>)
![alt text](<Screenshot 2025-11-09 165357.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
