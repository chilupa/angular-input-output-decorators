# AngularInputOutputDecorators

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

# Decorator
A decorator is simply a function that modifies definition of a class or properties inside a class. These decorators are also called as annotations and are mainly classified as two types. 

## Class Decorator 
A decorator that appears immediately before a class definition. 
For instance, `@Component()` decorator which is mentioned right before a class definition, has metadata that helps Angular to know how those classess or properties should work.   
```
@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrls: ['./app.component.css']
})
export class AppComponent {
  title = 'app';
}
```
Some other examples of class decorators are `@Injectable()`, `@NgModule()`, `@Directive()`, `@Pipe()`

## Class Field Decorator
A decorator that appears immediately before a field in a class definition.
For instance, `@Input()` and `@Output()`.
```
@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrls: ['./app.component.css'],
})
export class AppComponent {
  @Input() count;
  // code
}
```
# Quick Links 
From Angular Docs, [Decorator](https://angular.io/guide/glossary#decorator--decoration)

