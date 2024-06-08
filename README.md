# AI-Agents
Drag and Drop ML Models to build AI Agents with low code 
Code for Front End 
/**
 * v0 by Vercel.
 * @see https://v0.dev/t/kcvp77CTE3o
 * Documentation: https://v0.dev/docs#integrating-generated-code-into-your-nextjs-app
 */
import Link from "next/link"
import { Button } from "@/components/ui/button"
import { Card, CardHeader, CardTitle, CardDescription, CardContent } from "@/components/ui/card"
import { Label } from "@/components/ui/label"
import { Input } from "@/components/ui/input"

export default function Component() {
  return (
    <div className="flex flex-col min-h-screen">
      <header className="bg-gray-950 text-white py-4 px-6 flex items-center justify-between">
        <div className="flex items-center gap-4">
          <BotIcon className="h-6 w-6" />
          <h1 className="text-2xl font-bold">AI Agent Builder</h1>
        </div>
        <div className="flex items-center gap-4">
          <Link href="#" className="text-gray-400 hover:text-white" prefetch={false}>
            Docs
          </Link>
          <Link href="#" className="text-gray-400 hover:text-white" prefetch={false}>
            Pricing
          </Link>
          <Button variant="outline" className="text-gray-400 hover:text-white">
            Sign In
          </Button>
          <Button className="bg-blue-500 hover:bg-blue-600 text-white">Get Started</Button>
        </div>
      </header>
      <main className="flex-1 bg-gray-100 dark:bg-gray-950 py-12">
        <div className="max-w-6xl mx-auto px-4 md:px-6">
          <div className="grid md:grid-cols-2 gap-8">
            <div className="space-y-6">
              <h2 className="text-3xl font-bold">Build AI-powered apps, no code required.</h2>
              <p className="text-gray-600 dark:text-gray-400 text-lg">
                Drag and drop pre-built AI models to create custom AI agents. Our platform handles the backend
                infrastructure and deployment, so you can focus on building innovative applications.
              </p>
              <div className="flex gap-4">
                <Button className="bg-blue-500 hover:bg-blue-600 text-white">Get Started</Button>
                <Button variant="outline" className="text-blue-500 hover:text-blue-600">
                  Learn More
                </Button>
              </div>
            </div>
            <div>
              <img
                src="/placeholder.svg"
                alt="AI Agent Builder"
                width={600}
                height={400}
                className="rounded-lg shadow-lg"
              />
            </div>
          </div>
        </div>
      </main>
      <section className="bg-gray-950 text-white py-12">
        <div className="max-w-6xl mx-auto px-4 md:px-6">
          <h2 className="text-3xl font-bold mb-8">Features</h2>
          <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
            <div className="bg-gray-900 rounded-lg p-6 space-y-4">
              <PuzzleIcon className="h-8 w-8" />
              <h3 className="text-xl font-bold">Drag & Drop AI Models</h3>
              <p className="text-gray-400">
                Easily assemble custom AI agents by dragging and dropping pre-built machine learning algorithms and
                large language models onto the canvas.
              </p>
            </div>
            <div className="bg-gray-900 rounded-lg p-6 space-y-4">
              <CodeIcon className="h-8 w-8" />
              <h3 className="text-xl font-bold">No Coding Required</h3>
              <p className="text-gray-400">
                Our platform handles all the backend infrastructure and deployment, so you can build production-ready AI
                applications without writing a single line of code.
              </p>
            </div>
            <div className="bg-gray-900 rounded-lg p-6 space-y-4">
              <BoltIcon className="h-8 w-8" />
              <h3 className="text-xl font-bold">Powerful AI Capabilities</h3>
              <p className="text-gray-400">
                Leverage the latest advancements in machine learning and natural language processing to build
                intelligent, conversational AI agents.
              </p>
            </div>
            <div className="bg-gray-900 rounded-lg p-6 space-y-4">
              <RocketIcon className="h-8 w-8" />
              <h3 className="text-xl font-bold">Rapid Deployment</h3>
              <p className="text-gray-400">
                Once you've built your AI agent, our platform will handle the deployment, scaling, and maintenance, so
                you can focus on building your application.
              </p>
            </div>
            <div className="bg-gray-900 rounded-lg p-6 space-y-4">
              <SettingsIcon className="h-8 w-8" />
              <h3 className="text-xl font-bold">Customizable Configurations</h3>
              <p className="text-gray-400">
                Easily configure the inputs, outputs, and parameters of your AI models to tailor your agents to your
                specific use case.
              </p>
            </div>
            <div className="bg-gray-900 rounded-lg p-6 space-y-4">
              <ShieldIcon className="h-8 w-8" />
              <h3 className="text-xl font-bold">Secure and Compliant</h3>
              <p className="text-gray-400">
                Our platform is built with enterprise-grade security and compliance features to ensure your data and
                applications are protected.
              </p>
            </div>
          </div>
        </div>
      </section>
      <section className="bg-gray-100 dark:bg-gray-950 py-12">
        <div className="max-w-6xl mx-auto px-4 md:px-6">
          <h2 className="text-3xl font-bold mb-8">Get Started</h2>
          <div className="grid md:grid-cols-2 gap-8">
            <div>
              <Card>
                <CardHeader>
                  <CardTitle>Create an Account</CardTitle>
                  <CardDescription>Sign up to start building your first AI agent.</CardDescription>
                </CardHeader>
                <CardContent>
                  <form className="space-y-4">
                    <div className="space-y-2">
                      <Label htmlFor="name">Name</Label>
                      <Input id="name" placeholder="John Doe" />
                    </div>
                    <div className="space-y-2">
                      <Label htmlFor="email">Email</Label>
                      <Input id="email" type="email" placeholder="m@example.com" />
                    </div>
                    <div className="space-y-2">
                      <Label htmlFor="password">Password</Label>
                      <Input id="password" type="password" />
                    </div>
                    <Button className="w-full">Sign Up</Button>
                  </form>
                </CardContent>
              </Card>
            </div>
            <div>
              <Card>
                <CardHeader>
                  <CardTitle>Start Building</CardTitle>
                  <CardDescription>Drag and drop AI models to create your first AI agent.</CardDescription>
                </CardHeader>
                <CardContent>
                  <div className="space-y-4">
                    <div className="bg-gray-950 rounded-lg p-6 flex items-center justify-between">
                      <div className="flex items-center gap-4">
                        <PuzzleIcon className="h-8 w-8 text-blue-500" />
                        <div>
                          <h3 className="text-xl font-bold text-white">Natural Language Processing</h3>
                          <p className="text-gray-400">Understand and generate human-like text.</p>
                        </div>
                      </div>
                      <Button variant="outline" className="text-blue-500 hover:text-blue-600">
                        Add
                      </Button>
                    </div>
                    <div className="bg-gray-950 rounded-lg p-6 flex items-center justify-between">
                      <div className="flex items-center gap-4">
                        <BoltIcon className="h-8 w-8 text-green-500" />
                        <div>
                          <h3 className="text-xl font-bold text-white">Machine Learning</h3>
                          <p className="text-gray-400">
                            Leverage powerful algorithms for prediction and classification.
                          </p>
                        </div>
                      </div>
                      <Button variant="outline" className="text-green-500 hover:text-green-600">
                        Add
                      </Button>
                    </div>
                    <div className="bg-gray-950 rounded-lg p-6 flex items-center justify-between">
                      <div className="flex items-center gap-4">
                        <BotIcon className="h-8 w-8 text-purple-500" />
                        <div>
                          <h3 className="text-xl font-bold text-white">Conversational AI</h3>
                          <p className="text-gray-400">Build intelligent, chatbot-like experiences.</p>
                        </div>
                      </div>
                      <Button variant="outline" className="text-purple-500 hover:text-purple-600">
                        Add
                      </Button>
                    </div>
                    <div className="bg-gray-950 rounded-lg p-6 flex items-center justify-between">
                      <div className="flex items-center gap-4">
                        <BarChartIcon className="h-8 w-8 text-orange-500" />
                        <div>
                          <h3 className="text-xl font-bold text-white">Predictive Analytics</h3>
                          <p className="text-gray-400">Forecast trends and make data-driven decisions.</p>
                        </div>
                      </div>
                      <Button variant="outline" className="text-orange-500 hover:text-orange-600">
                        Add
                      </Button>
                    </div>
                    <div className="bg-gray-950 rounded-lg p-6 flex items-center justify-between">
                      <div className="flex items-center gap-4">
                        <ImageIcon className="h-8 w-8 text-pink-500" />
                        <div>
                          <h3 className="text-xl font-bold text-white">Computer Vision</h3>
                          <p className="text-gray-400">Analyze and understand visual data.</p>
                        </div>
                      </div>
                      <Button variant="outline" className="text-pink-500 hover:text-pink-600">
                        Add
                      </Button>
                    </div>
                    <div className="bg-gray-950 rounded-lg p-6 flex items-center justify-between">
                      <div className="flex items-center gap-4">
                        <FileMusicIcon className="h-8 w-8 text-indigo-500" />
                        <div>
                          <h3 className="text-xl font-bold text-white">Audio Processing</h3>
                          <p className="text-gray-400">Understand and generate audio content.</p>
                        </div>
                      </div>
                      <Button variant="outline" className="text-indigo-500 hover:text-indigo-600">
                        Add
                      </Button>
                    </div>
                    <div className="bg-gray-950 rounded-lg p-6 flex items-center justify-between">
                      <div className="flex items-center gap-4">
                        <CuboidIcon className="h-8 w-8 text-teal-500" />
                        <div>
                          <h3 className="text-xl font-bold text-white">3D Modeling</h3>
                          <p className="text-gray-400">Create and manipulate 3D models.</p>
                        </div>
                      </div>
                      <Button variant="outline" className="text-teal-500 hover:text-teal-600">
                        Add
                      </Button>
                    </div>
                    <div className="bg-gray-950 rounded-lg p-6 flex items-center justify-between">
                      <div className="flex items-center gap-4">
                        <GaugeIcon className="h-8 w-8 text-yellow-500" />
                        <div>
                          <h3 className="text-xl font-bold text-white">Anomaly Detection</h3>
                          <p className="text-gray-400">Identify unusual patterns in data.</p>
                        </div>
                      </div>
                      <Button variant="outline" className="text-yellow-500 hover:text-yellow-600">
                        Add
                      </Button>
                    </div>
                    <div className="bg-gray-950 rounded-lg p-6 flex items-center justify-between">
                      <div className="flex items-center gap-4">
                        <Dice1Icon className="h-8 w-8 text-red-500" />
                        <div>
                          <h3 className="text-xl font-bold text-white">Reinforcement Learning</h3>
                          <p className="text-gray-400">Train agents to make optimal decisions.</p>
                        </div>
                      </div>
                      <Button variant="outline" className="text-red-500 hover:text-red-600">
                        Add
                      </Button>
                    </div>
                    <div className="bg-gray-950 rounded-lg p-6 flex items-center justify-between">
                      <div className="flex items-center gap-4">
                        <AtomIcon className="h-8 w-8 text-cyan-500" />
                        <div>
                          <h3 className="text-xl font-bold text-white">Generative AI</h3>
                          <p className="text-gray-400">Generate new content, images, and ideas.</p>
                        </div>
                      </div>
                      <Button variant="outline" className="text-cyan-500 hover:text-cyan-600">
                        Add
                      </Button>
                    </div>
                  </div>
                </CardContent>
              </Card>
            </div>
          </div>
        </div>
      </section>
      <footer className="bg-gray-950 text-white py-6">
        <div className="max-w-6xl mx-auto px-4 md:px-6 flex items-center justify-between">
          <div className="flex items-center gap-4">
            <BotIcon className="h-6 w-6" />
            <span className="text-sm">© 2023 AI Agent Builder. All rights reserved.</span>
          </div>
          <div className="flex items-center gap-4">
            <Link href="#" className="text-gray-400 hover:text-white" prefetch={false}>
              Terms
            </Link>
            <Link href="#" className="text-gray-400 hover:text-white" prefetch={false}>
              Privacy
            </Link>
            <Link href="#" className="text-gray-400 hover:text-white" prefetch={false}>
              Contact
            </Link>
          </div>
        </div>
      </footer>
    </div>
  )
}

function AtomIcon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <circle cx="12" cy="12" r="1" />
      <path d="M20.2 20.2c2.04-2.03.02-7.36-4.5-11.9-4.54-4.52-9.87-6.54-11.9-4.5-2.04 2.03-.02 7.36 4.5 11.9 4.54 4.52 9.87 6.54 11.9 4.5Z" />
      <path d="M15.7 15.7c4.52-4.54 6.54-9.87 4.5-11.9-2.03-2.04-7.36-.02-11.9 4.5-4.52 4.54-6.54 9.87-4.5 11.9 2.03 2.04 7.36.02 11.9-4.5Z" />
    </svg>
  )
}


function BarChartIcon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <line x1="12" x2="12" y1="20" y2="10" />
      <line x1="18" x2="18" y1="20" y2="4" />
      <line x1="6" x2="6" y1="20" y2="16" />
    </svg>
  )
}


function BoltIcon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z" />
      <circle cx="12" cy="12" r="4" />
    </svg>
  )
}


function BotIcon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <path d="M12 8V4H8" />
      <rect width="16" height="12" x="4" y="8" rx="2" />
      <path d="M2 14h2" />
      <path d="M20 14h2" />
      <path d="M15 13v2" />
      <path d="M9 13v2" />
    </svg>
  )
}


function CodeIcon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <polyline points="16 18 22 12 16 6" />
      <polyline points="8 6 2 12 8 18" />
    </svg>
  )
}


function CuboidIcon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <path d="m21.12 6.4-6.05-4.06a2 2 0 0 0-2.17-.05L2.95 8.41a2 2 0 0 0-.95 1.7v5.82a2 2 0 0 0 .88 1.66l6.05 4.07a2 2 0 0 0 2.17.05l9.95-6.12a2 2 0 0 0 .95-1.7V8.06a2 2 0 0 0-.88-1.66Z" />
      <path d="M10 22v-8L2.25 9.15" />
      <path d="m10 14 11.77-6.87" />
    </svg>
  )
}


function Dice1Icon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <rect width="18" height="18" x="3" y="3" rx="2" ry="2" />
      <path d="M12 12h.01" />
    </svg>
  )
}


function FileMusicIcon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <circle cx="14" cy="16" r="2" />
      <circle cx="6" cy="18" r="2" />
      <path d="M4 12.4V4a2 2 0 0 1 2-2h8.5L20 7.5V20a2 2 0 0 1-2 2h-7.5" />
      <path d="M8 18v-7.7L16 9v7" />
    </svg>
  )
}


function GaugeIcon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <path d="m12 14 4-4" />
      <path d="M3.34 19a10 10 0 1 1 17.32 0" />
    </svg>
  )
}


function ImageIcon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <rect width="18" height="18" x="3" y="3" rx="2" ry="2" />
      <circle cx="9" cy="9" r="2" />
      <path d="m21 15-3.086-3.086a2 2 0 0 0-2.828 0L6 21" />
    </svg>
  )
}


function PuzzleIcon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <path d="M19.439 7.85c-.049.322.059.648.289.878l1.568 1.568c.47.47.706 1.087.706 1.704s-.235 1.233-.706 1.704l-1.611 1.611a.98.98 0 0 1-.837.276c-.47-.07-.802-.48-.968-.925a2.501 2.501 0 1 0-3.214 3.214c.446.166.855.497.925.968a.979.979 0 0 1-.276.837l-1.61 1.61a2.404 2.404 0 0 1-1.705.707 2.402 2.402 0 0 1-1.704-.706l-1.568-1.568a1.026 1.026 0 0 0-.877-.29c-.493.074-.84.504-1.02.968a2.5 2.5 0 1 1-3.237-3.237c.464-.18.894-.527.967-1.02a1.026 1.026 0 0 0-.289-.877l-1.568-1.568A2.402 2.402 0 0 1 1.998 12c0-.617.236-1.234.706-1.704L4.23 8.77c.24-.24.581-.353.917-.303.515.077.877.528 1.073 1.01a2.5 2.5 0 1 0 3.259-3.259c-.482-.196-.933-.558-1.01-1.073-.05-.336.062-.676.303-.917l1.525-1.525A2.402 2.402 0 0 1 12 1.998c.617 0 1.234.236 1.704.706l1.568 1.568c.23.23.556.338.877.29.493-.074.84-.504 1.02-.968a2.5 2.5 0 1 1 3.237 3.237c-.464.18-.894.527-.967 1.02Z" />
    </svg>
  )
}


function RocketIcon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <path d="M4.5 16.5c-1.5 1.26-2 5-2 5s3.74-.5 5-2c.71-.84.7-2.13-.09-2.91a2.18 2.18 0 0 0-2.91-.09z" />
      <path d="m12 15-3-3a22 22 0 0 1 2-3.95A12.88 12.88 0 0 1 22 2c0 2.72-.78 7.5-6 11a22.35 22.35 0 0 1-4 2z" />
      <path d="M9 12H4s.55-3.03 2-4c1.62-1.08 5 0 5 0" />
      <path d="M12 15v5s3.03-.55 4-2c1.08-1.62 0-5 0-5" />
    </svg>
  )
}


function SettingsIcon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <path d="M12.22 2h-.44a2 2 0 0 0-2 2v.18a2 2 0 0 1-1 1.73l-.43.25a2 2 0 0 1-2 0l-.15-.08a2 2 0 0 0-2.73.73l-.22.38a2 2 0 0 0 .73 2.73l.15.1a2 2 0 0 1 1 1.72v.51a2 2 0 0 1-1 1.74l-.15.09a2 2 0 0 0-.73 2.73l.22.38a2 2 0 0 0 2.73.73l.15-.08a2 2 0 0 1 2 0l.43.25a2 2 0 0 1 1 1.73V20a2 2 0 0 0 2 2h.44a2 2 0 0 0 2-2v-.18a2 2 0 0 1 1-1.73l.43-.25a2 2 0 0 1 2 0l.15.08a2 2 0 0 0 2.73-.73l.22-.39a2 2 0 0 0-.73-2.73l-.15-.08a2 2 0 0 1-1-1.74v-.5a2 2 0 0 1 1-1.74l.15-.09a2 2 0 0 0 .73-2.73l-.22-.38a2 2 0 0 0-2.73-.73l-.15.08a2 2 0 0 1-2 0l-.43-.25a2 2 0 0 1-1-1.73V4a2 2 0 0 0-2-2z" />
      <circle cx="12" cy="12" r="3" />
    </svg>
  )
}


function ShieldIcon(props) {
  return (
    <svg
      {...props}
      xmlns="http://www.w3.org/2000/svg"
      width="24"
      height="24"
      viewBox="0 0 24 24"
      fill="none"
      stroke="currentColor"
      strokeWidth="2"
      strokeLinecap="round"
      strokeLinejoin="round"
    >
      <path d="M20 13c0 5-3.5 7.5-7.66 8.95a1 1 0 0 1-.67-.01C7.5 20.5 4 18 4 13V6a1 1 0 0 1 1-1c2 0 4.5-1.2 6.24-2.72a1.17 1.17 0 0 1 1.52 0C14.51 3.81 17 5 19 5a1 1 0 0 1 1 1z" />
    </svg>
  )
}
