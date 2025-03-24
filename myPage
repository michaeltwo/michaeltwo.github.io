export default function FavoriteTools() {
  const tools = [
    { name: "Universal Path Converter", description: "Seamless path conversions across OS." },
    { name: "Django", description: "A high-level Python web framework." },
    { name: "PostgreSQL", description: "A powerful, open-source database system." }
  ];

  return (
    <div className="p-5 max-w-2xl mx-auto">
      <h1 className="text-3xl font-bold mb-4">My Favorite Tools</h1>
      <ul className="space-y-4">
        {tools.map((tool, index) => (
          <li key={index} className="p-4 border rounded-lg shadow">
            <h2 className="text-xl font-semibold">{tool.name}</h2>
            <p className="text-gray-600">{tool.description}</p>
          </li>
        ))}
      </ul>
    </div>
  );
}
