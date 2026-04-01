import React, { useState } from "react";
import { ToastContainer, toast } from "react-toastify";
import "react-toastify/dist/ReactToastify.css";

// ================= PRODUCT JSON DATA =================
const productsData = [
  {
    id: 1,
    name: "Resume Builder Pro",
    description: "Create ATS-friendly resumes quickly.",
    price: 9,
    period: "monthly",
    tag: "popular",
    tagType: "Popular",
    icon: "📄",
    features: ["100+ templates", "ATS optimization", "Export PDF"]
  },
  {
    id: 2,
    name: "Portfolio Designer",
    description: "Build developer portfolios easily.",
    price: 15,
    period: "monthly",
    tag: "best",
    tagType: "Best Seller",
    icon: "🎨",
    features: ["Drag & drop", "Custom themes", "SEO optimized"]
  },
  {
    id: 3,
    name: "Social Media Scheduler",
    description: "Plan posts across platforms automatically.",
    price: 20,
    period: "monthly",
    tag: "new",
    tagType: "New",
    icon: "📱",
    features: ["Auto posting", "Analytics", "Calendar view"]
  },
  {
    id: 4,
    name: "Design Toolkit",
    description: "Professional UI kits and assets.",
    price: 49,
    period: "one-time",
    tag: "popular",
    tagType: "Popular",
    icon: "🧰",
    features: ["500+ components", "Figma ready", "Lifetime access"]
  },
  {
    id: 5,
    name: "Writing Assistant",
    description: "Improve grammar instantly.",
    price: 5,
    period: "monthly",
    tag: "best",
    tagType: "Best Seller",
    icon: "✍️",
    features: ["Grammar check", "Tone suggestions", "Auto correction"]
  },
  {
    id: 6,
    name: "Video Editor Lite",
    description: "Fast editing for creators.",
    price: 30,
    period: "yearly",
    tag: "new",
    tagType: "New",
    icon: "🎬",
    features: ["Transitions", "HD export", "Audio sync"]
  },
  {
    id: 7,
    name: "Startup Toolkit",
    description: "Essential startup templates.",
    price: 59,
    period: "one-time",
    tag: "popular",
    tagType: "Popular",
    icon: "🚀",
    features: ["Pitch deck", "Financial sheets", "Roadmap planner"]
  },
  {
    id: 8,
    name: "Task Manager Pro",
    description: "Organize tasks efficiently.",
    price: 12,
    period: "monthly",
    tag: "best",
    tagType: "Best Seller",
    icon: "✅",
    features: ["Kanban board", "Reminders", "Team sync"]
  }
];

export default function App() {
  const [cart, setCart] = useState([]);
  const [view, setView] = useState("products");

  // ================= ADD TO CART =================
  const addToCart = (product) => {
    setCart((prev) => [...prev, product]);
    toast.success(`${product.name} added to cart`);
  };

  // ================= REMOVE ITEM =================
  const removeFromCart = (id) => {
    setCart((prev) => prev.filter((item) => item.id !== id));
    toast.error("Product removed from cart");
  };

  // ================= CHECKOUT =================
  const checkout = () => {
    setCart([]);
    toast.success("Checkout complete successfully");
  };

  const totalPrice = cart.reduce((acc, item) => acc + item.price, 0);

  return (
    <div className="bg-gray-50 min-h-screen">
      <ToastContainer />

      {/* ================= NAVBAR ================= */}
      <nav className="navbar bg-white shadow px-10">
        <h1 className="text-2xl font-bold">Digital Tools Store</h1>

        <div className="indicator">
          <span className="indicator-item badge badge-primary">
            {cart.length}
          </span>
          <button className="btn btn-ghost text-xl">🛒</button>
        </div>
      </nav>

      {/* ================= BANNER ================= */}
      <section className="hero py-16">
        <div className="hero-content text-center">
          <div>
            <h1 className="text-5xl font-bold">
              Smart Digital Tools for Students & Creators
            </h1>
            <p className="py-6 max-w-xl mx-auto">
              Explore powerful productivity tools that help you design, write,
              plan, and build faster with modern workflows.
            </p>

            <div className="flex gap-4 justify-center">
              <button className="btn btn-primary">Explore Tools</button>
              <button className="btn btn-outline">View Pricing</button>
            </div>
          </div>
        </div>
      </section>

      {/* ================= STATS SECTION ================= */}
      <section className="grid md:grid-cols-4 gap-6 px-10 pb-12">
        <Stat title="Active Users" value="15K+" />
        <Stat title="Premium Tools" value="60+" />
        <Stat title="Downloads" value="40K+" />
        <Stat title="Positive Reviews" value="8K+" />
      </section>

      {/* ================= TOGGLE BUTTONS ================= */}
      <div className="flex justify-center gap-5 my-10">
        <button
          onClick={() => setView("products")}
          className="btn btn-primary"
        >
          Products
        </button>

        <button
          onClick={() => setView("cart")}
          className="btn btn-secondary"
        >
          Cart ({cart.length})
        </button>
      </div>

      {/* ================= PRODUCTS SECTION ================= */}
      {view === "products" && (
        <section className="grid lg:grid-cols-3 md:grid-cols-2 gap-6 px-10">
          {productsData.map((product) => (
            <ProductCard
              key={product.id}
              product={product}
              addToCart={addToCart}
            />
          ))}
        </section>
      )}

      {/* ================= CART SECTION ================= */}
      {view === "cart" && (
        <section className="px-10 max-w-3xl mx-auto">
          {cart.length === 0 ? (
            <h2 className="text-center text-gray-500 text-xl">
              Your cart is empty
            </h2>
          ) : (
            <>
              {cart.map((item) => (
                <CartItem
                  key={item.id}
                  item={item}
                  removeFromCart={removeFromCart}
                />
              ))}

              <div className="text-right font-bold text-lg mt-4">
                Total: ${totalPrice}
              </div>

              <div className="text-center mt-6">
                <button className="btn btn-success" onClick={checkout}>
                  Proceed to Checkout
                </button>
              </div>
            </>
          )}
        </section>
      )}

      {/* ================= STEPS SECTION ================= */}
      <section className="py-20 bg-white text-center">
        <h2 className="text-3xl font-bold mb-10">How It Works</h2>

        <div className="grid md:grid-cols-3 gap-6 px-10">
          <Step
            title="Browse"
            desc="Explore professional digital tools easily"
          />

          <Step
            title="Add to Cart"
            desc="Select tools you want instantly"
          />

          <Step
            title="Checkout"
            desc="Secure and fast checkout process"
          />
        </div>
      </section>

      {/* ================= PRICING SECTION ================= */}
      <section className="py-20 text-center">
        <h2 className="text-3xl font-bold mb-8">Flexible Pricing Plans</h2>

        <div className="grid md:grid-cols-3 gap-6 px-10">
          <PricingCard
            title="Starter"
            price="Free"
            features={["Basic Tools", "Community Support", "Limited Access"]}
          />

          <PricingCard
            title="Professional"
            price="$12/month"
            features={["All Tools", "Priority Support", "Cloud Backup"]}
          />

          <PricingCard
            title="Enterprise"
            price="$49/month"
            features={[
              "Unlimited Access",
              "Team Collaboration",
              "Dedicated Support"
            ]}
          />
        </div>
      </section>

      {/* ================= FOOTER ================= */}
      <footer className="bg-gray-900 text-white text-center py-8">
        <p className="font-semibold">Digital Tools Store</p>
        <p className="text-sm opacity-70">
          Helping students and creators boost productivity with modern tools
        </p>
        <p className="text-xs mt-2">© 2026 All Rights Reserved</p>
      </footer>
    </div>
  );
}

// ================= PRODUCT CARD =================
function ProductCard({ product, addToCart }) {
  const [clicked, setClicked] = useState(false);

  const handleClick = () => {
    addToCart(product);
    setClicked(true);
  };

  return (
    <div className="card bg-white shadow-lg">
      <div className="card-body">
        <h2 className="card-title">
          {product.icon} {product.name}
        </h2>

        <p>{product.description}</p>

        <p className="font-semibold">
          ${product.price} / {product.period}
        </p>

        <span className="badge badge-accent">
          {product.tagType}
        </span>

        <ul className="text-sm mt-2">
          {product.features.map((f, i) => (
            <li key={i}>• {f}</li>
          ))}
        </ul>

        <button
          onClick={handleClick}
          className="btn btn-primary mt-3"
        >
          {clicked ? "Added to Cart" : "Buy Now"}
        </button>
      </div>
    </div>
  );
}

// ================= CART ITEM =================
function CartItem({ item, removeFromCart }) {
  return (
    <div className="flex justify-between items-center bg-white shadow p-4 rounded mb-3">
      <span>
        {item.icon} {item.name}
      </span>

      <span>${item.price}</span>

      <button
        className="btn btn-error btn-sm"
        onClick={() => removeFromCart(item.id)}
      >
        Remove
      </button>
    </div>
  );
}

// ================= STATS =================
function Stat({ title, value }) {
  return (
    <div className="bg-white shadow rounded-xl p-6 text-center">
      <h3 className="text-2xl font-bold">{value}</h3>
      <p className="text-gray-500">{title}</p>
    </div>
  );
}

// ================= STEPS =================
function Step({ title, desc }) {
  return (
    <div className="bg-gray-100 p-6 rounded-xl">
      <h4 className="font-semibold text-lg">{title}</h4>
      <p className="text-sm text-gray-600">{desc}</p>
    </div>
  );
}

// ================= PRICING CARD =================
function PricingCard({ title, price, features }) {
  return (
    <div className="card bg-white shadow-xl">
      <div className="card-body">
        <h2 className="card-title justify-center">{title}</h2>
        <p className="text-3xl font-bold">{price}</p>

        <ul className="text-sm">
          {features.map((f, i) => (
            <li key={i}>• {f}</li>
          ))}
        </ul>

        <button className="btn btn-outline mt-3">Choose Plan</button>
      </div>
    </div>
  );
}
