import React from "react";
import { BrowserRouter as Router, Route, Link, Routes } from "react-router-dom";

const Marketplace = () => <div className="p-4 text-center">Marketplace Content</div>;
const MyCollection = () => <div className="p-4 text-center">My Collection Content</div>;

const App = () => {
  return (
    <Router>
      <div className="flex flex-col h-screen justify-between">
        <div className="flex-grow">
          <Routes>
            <Route path="/marketplace" element={<Marketplace />} />
            <Route path="/my-collection" element={<MyCollection />} />
          </Routes>
        </div>
        <nav className="bg-gray-800 p-4 flex justify-around text-white">
          <Link to="/marketplace" className="px-4 py-2">Marketplace</Link>
          <Link to="/my-collection" className="px-4 py-2">My Collection</Link>
        </nav>
      </div>
    </Router>
  );
};

export default App;
