/**
 * v0 by Vercel.
 * @see https://v0.dev/t/0M8BEaSaj5l
 * Documentation: https://v0.dev/docs#integrating-generated-code-into-your-nextjs-app
 */
export default function Component() {
  return (
    <div className="flex flex-col min-h-screen bg-background">
      <header className="bg-primary text-primary-foreground py-4 px-6">
        <h1 className="text-3xl font-bold">The History of Engineering</h1>
      </header>
      <main className="flex-1 py-12 px-6 md:px-12 lg:px-20">
        <section className="mb-12">
          <h2 className="text-2xl font-bold mb-4">Conceptual Map of Engineering History</h2>
          <div className="bg-muted rounded-lg p-6">
            <img
              src="/placeholder.svg"
              width="1200"
              height="800"
              alt="Conceptual map of engineering history"
              className="w-full h-auto"
              style={{ aspectRatio: "1200/800", objectFit: "cover" }}
            />
          </div>
        </section>
        <section>
          <h2 className="text-2xl font-bold mb-4">Timeline of Groundbreaking Inventions</h2>
          <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div className="bg-muted rounded-lg p-6">
              <h3 className="text-xl font-bold mb-2">Ancient Inventions</h3>
              <ul className="space-y-2 text-muted-foreground">
                <li>
                  <span className="font-medium">Wheel</span> - Invented around 3500 BC, the wheel revolutionized
                  transportation and enabled the development of many other technologies.
                  <img
                    src="/placeholder.svg"
                    width="200"
                    height="200"
                    alt="Wheel"
                    className="mt-2 rounded-lg"
                    style={{ aspectRatio: "200/200", objectFit: "cover" }}
                  />
                </li>
                <li>
                  <span className="font-medium">Archimedes' Screw</span> - Invented around 250 BC, this water-lifting
                  device was a crucial innovation in ancient irrigation and drainage systems.
                  <img
                    src="/placeholder.svg"
                    width="200"
                    height="200"
                    alt="Archimedes' Screw"
                    className="mt-2 rounded-lg"
                    style={{ aspectRatio: "200/200", objectFit: "cover" }}
                  />
                </li>
                <li>
                  <span className="font-medium">Catapult</span> - Developed in the 4th century BC, the catapult was a
                  powerful siege weapon that played a significant role in ancient warfare.
                  <img
                    src="/placeholder.svg"
                    width="200"
                    height="200"
                    alt="Catapult"
                    className="mt-2 rounded-lg"
                    style={{ aspectRatio: "200/200", objectFit: "cover" }}
                  />
                </li>
              </ul>
            </div>
            <div className="bg-muted rounded-lg p-6">
              <h3 className="text-xl font-bold mb-2">Medieval and Renaissance Inventions</h3>
              <ul className="space-y-2 text-muted-foreground">
                <li>
                  <span className="font-medium">Mechanical Clock</span> - Invented in the 13th century, the mechanical
                  clock was a groundbreaking innovation that revolutionized timekeeping.
                  <img
                    src="/placeholder.svg"
                    width="200"
                    height="200"
                    alt="Mechanical Clock"
                    className="mt-2 rounded-lg"
                    style={{ aspectRatio: "200/200", objectFit: "cover" }}
                  />
                </li>
                <li>
                  <span className="font-medium">Printing Press</span> - Developed by Johannes Gutenberg in the 15th
                  century, the printing press enabled the mass production and dissemination of information.
                  <img
                    src="/placeholder.svg"
                    width="200"
                    height="200"
                    alt="Printing Press"
                    className="mt-2 rounded-lg"
                    style={{ aspectRatio: "200/200", objectFit: "cover" }}
                  />
                </li>
                <li>
                  <span className="font-medium">Telescope</span> - Invented in the early 17th century, the telescope
                  opened up new frontiers in astronomy and scientific exploration.
                  <img
                    src="/placeholder.svg"
                    width="200"
                    height="200"
                    alt="Telescope"
                    className="mt-2 rounded-lg"
                    style={{ aspectRatio: "200/200", objectFit: "cover" }}
                  />
                </li>
              </ul>
            </div>
            <div className="bg-muted rounded-lg p-6">
              <h3 className="text-xl font-bold mb-2">Industrial Revolution Inventions</h3>
              <ul className="space-y-2 text-muted-foreground">
                <li>
                  <span className="font-medium">Steam Engine</span> - Developed in the 18th century, the steam engine
                  powered the Industrial Revolution and enabled the mechanization of many industries.
                  <img
                    src="/placeholder.svg"
                    width="200"
                    height="200"
                    alt="Steam Engine"
                    className="mt-2 rounded-lg"
                    style={{ aspectRatio: "200/200", objectFit: "cover" }}
                  />
                </li>
                <li>
                  <span className="font-medium">Telegraph</span> - Invented in the 1830s, the telegraph revolutionized
                  long-distance communication and paved the way for modern telecommunications.
                  <img
                    src="/placeholder.svg"
                    width="200"
                    height="200"
                    alt="Telegraph"
                    className="mt-2 rounded-lg"
                    style={{ aspectRatio: "200/200", objectFit: "cover" }}
                  />
                </li>
                <li>
                  <span className="font-medium">Internal Combustion Engine</span> - Developed in the late 19th century,
                  the internal combustion engine powered the rise of automobiles and aviation.
                  <img
                    src="/placeholder.svg"
                    width="200"
                    height="200"
                    alt="Internal Combustion Engine"
                    className="mt-2 rounded-lg"
                    style={{ aspectRatio: "200/200", objectFit: "cover" }}
                  />
                </li>
              </ul>
            </div>
            <div className="bg-muted rounded-lg p-6">
              <h3 className="text-xl font-bold mb-2">Modern Inventions</h3>
              <ul className="space-y-2 text-muted-foreground">
                <li>
                  <span className="font-medium">Transistor</span> - Invented in 1947, the transistor enabled the
                  development of modern electronics and paved the way for the digital revolution.
                  <img
                    src="/placeholder.svg"
                    width="200"
                    height="200"
                    alt="Transistor"
                    className="mt-2 rounded-lg"
                    style={{ aspectRatio: "200/200", objectFit: "cover" }}
                  />
                </li>
                <li>
                  <span className="font-medium">Personal Computer</span> - Developed in the 1970s, the personal computer
                  transformed how people work, communicate, and access information.
                  <img
                    src="/placeholder.svg"
                    width="200"
                    height="200"
                    alt="Personal Computer"
                    className="mt-2 rounded-lg"
                    style={{ aspectRatio: "200/200", objectFit: "cover" }}
                  />
                </li>
                <li>
                  <span className="font-medium">Internet</span> - Emerged in the 1990s, the internet has revolutionized
                  global communication, commerce, and access to information.
                  <img
                    src="/placeholder.svg"
                    width="200"
                    height="200"
                    alt="Internet"
                    className="mt-2 rounded-lg"
                    style={{ aspectRatio: "200/200", objectFit: "cover" }}
                  />
                </li>
              </ul>
            </div>
          </div>
        </section>
      </main>
      <footer className="bg-primary text-primary-foreground py-4 px-6 text-sm">
        <p>&copy; 2024 Acme Inc. All rights reserved.</p>
      </footer>
    </div>
  )
}
