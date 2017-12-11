## Angular - Questions from Craft Academy course material

### Where in the file structure is the component file located?
In src/app   

### What is the decorator, and what information does the decorator have?
The decorator in this case is `@Component`it has metadata about the selector, templateUrl, styleUrls; for an example see below. It allows us to attach additional information to a class.

``@Component({
  selector: 'app-comment',
  templateUrl: './comment.component.html',
  styleUrls: ['./comment.component.css']
})``


### Where is the template file located?
The template for Comment is in src/app/comment.

### How do we add our component to a view?


### Can we add our component to the index file?

### Is it possible to add the component to the app.component.html file?
