# Node.js Express.js and MongoDB
An application of basic CRUD operations based on node.js.

## Route

```
// Create a new tutorial
router.post("/", tutorials.create);

// Retrieve all Tutorials
router.get("/", tutorials.findAll);

// Retrieve all published Tutorials
router.get("/published", tutorials.findAllPublished);

// Retrieve a single Tutorial with id
// router.get("/:id". tutorials.findOne2);

// Update a Tutorial with id 
router.put("/:id", tutorials.update);

// Delete a Tutorial with id 
router.delete("/:id", tutorials.delete);

// Delete all Tutorials 
router.delete("/", tutorials.deleteAll)

app.use('/api/tutorials', router);```
