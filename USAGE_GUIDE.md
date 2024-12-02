# Guide for Usage

1. **Install WordIndexer**: Use NuGet:  
   `Install-Package WordIndexer`
2. **Initialize**:  
   ```csharp
   var indexer = new WordIndexer();
3. **Provide URL**:  
   ```csharp
   var results = indexer.Analyze("https://example.com");
4. **Generate Diagrams:**:  
   ```csharp
   indexer.GenerateDiagram(results, "output.png");
