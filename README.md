export default function RydeWebsite() {
  return (
    <div className="min-h-screen bg-black text-white font-sans">
      {/* Header */}
      <header className="border-b border-yellow-600/40 px-8 py-5 flex items-center justify-between">
        <div className="flex items-center gap-4">
          <img src="/mnt/data/95EC03B9-B890-41D7-9166-DA475A7C8E58.jpeg" alt="RYDE logo" className="h-12 w-12 rounded-xl object-cover border border-yellow-600/40" />
          <div>
            <h1 className="text-2xl font-bold tracking-[0.25em] text-yellow-500">RYDE</h1>
          <p className="text-sm text-zinc-400 italic">Travel Beyond</p>
          </div>
        </div>
        <nav className="hidden md:flex gap-8 text-sm text-zinc-300">
          <a href="#about" className="hover:text-yellow-500">About</a>
          <a href="#services" className="hover:text-yellow-500">Services</a>
          <a href="#drivers" className="hover:text-yellow-500">Drivers</a>
          <a href="#investors" className="hover:text-yellow-500">Investors</a>
        </nav>
      </header>

      {/* Hero */}\n      <section className="relative overflow-hidden px-8 md:px-16 py-24 grid md:grid-cols-2 gap-12 items-center">\n        <img src="/mnt/data/95EC03B9-B890-41D7-9166-DA475A7C8E58.jpeg" alt="RYDE watermark" className="absolute right-8 top-1/2 -translate-y-1/2 w-96 h-96 object-contain opacity-10 pointer-events-none" />
        <div>
          <p className="text-yellow-500 uppercase tracking-[0.3em] text-sm mb-4">Premium Uber Black Fleet Partner</p>
          <h2 className="text-5xl md:text-6xl font-bold leading-tight mb-6">
            India’s Premium <span className="text-yellow-500">Mobility Infrastructure</span>
          </h2>
          <p className="text-zinc-300 text-lg leading-8 max-w-xl">
            RYDE is a luxury fleet management and driver enablement platform powering Uber Black operations with premium vehicles, elite chauffeurs, and intelligent earnings tools.
          </p>
          <div className="mt-8 flex gap-4">
            <button className="bg-yellow-500 text-black px-6 py-3 rounded-2xl font-semibold">Partner With Us</button>
            <button className="border border-yellow-500 text-yellow-500 px-6 py-3 rounded-2xl font-semibold">View Deck</button>
          </div>
        </div>
        <div className="bg-zinc-900 border border-yellow-600/30 rounded-3xl p-10 shadow-2xl">
          <div className="grid grid-cols-2 gap-6">
            <div className="p-6 rounded-2xl bg-zinc-950 border border-zinc-800">
              <p className="text-zinc-400 text-sm">Fleet Goal</p>
              <h3 className="text-3xl font-bold text-yellow-500 mt-2">100+</h3>
            </div>
            <div className="p-6 rounded-2xl bg-zinc-950 border border-zinc-800">
              <p className="text-zinc-400 text-sm">ARR Target</p>
              <h3 className="text-3xl font-bold text-yellow-500 mt-2">₹10Cr</h3>
            </div>
            <div className="p-6 rounded-2xl bg-zinc-950 border border-zinc-800">
              <p className="text-zinc-400 text-sm">Seed Round</p>
              <h3 className="text-3xl font-bold text-yellow-500 mt-2">₹3Cr</h3>
            </div>
            <div className="p-6 rounded-2xl bg-zinc-950 border border-zinc-800">
              <p className="text-zinc-400 text-sm">Equity</p>
              <h3 className="text-3xl font-bold text-yellow-500 mt-2">20%</h3>
            </div>
          </div>
        </div>
      </section>

      {/* Brand Guidelines */}
      <section id="about" className="px-8 md:px-16 py-20 border-t border-zinc-900">
        <h3 className="text-3xl font-bold mb-10">Brand Guidelines</h3>
        <div className="grid md:grid-cols-3 gap-8">
          <div className="rounded-3xl border border-zinc-800 p-8 bg-zinc-950">
            <h4 className="text-yellow-500 font-semibold mb-4">Colors</h4>
            <p className="text-zinc-300">Primary: Luxury Black</p>
            <p className="text-zinc-300">Accent: Executive Gold</p>
            <p className="text-zinc-300">Text: Pure White / Slate Gray</p>
          </div>
          <div className="rounded-3xl border border-zinc-800 p-8 bg-zinc-950">
            <h4 className="text-yellow-500 font-semibold mb-4">Typography</h4>
            <p className="text-zinc-300">Headlines: Bold uppercase with wide tracking</p>
            <p className="text-zinc-300">Body: Clean sans-serif, high readability</p>
          </div>
          <div className="rounded-3xl border border-zinc-800 p-8 bg-zinc-950">
            <h4 className="text-yellow-500 font-semibold mb-4">Tone</h4>
            <p className="text-zinc-300">Premium, trustworthy, executive, growth-focused</p>
          </div>
        </div>
      </section>
    </div>
  )
}
