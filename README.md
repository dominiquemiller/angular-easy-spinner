# angular-easy-spinner
Module to add global spinner to your Angular projects.

## Installation
Clone repo and place easy-spinner directory in your app directory:

<pre style="max-height: 100px;"><code>src
    │    ├── app
    │    │   ├── easy-spinner</code></pre>
    
Then import SpinnerModule in app.module.ts:
```
import { SpinnerModule } from 'path.to.module';

@NgModule({
  declarations: [AppComponent],
  imports: [
    // Angular Modules
    BrowserModule,
    CommonModule,
    
    // Custom Modules
    SpinnerModule,
  ],
  providers: [],
  bootstrap: [AppComponent]
})
```

## Usage

To use in a component, simply import the the spinner service and use the show or hide methods:
```
export class SomeComponent {

    constructor( private spinner: SpinnerService ) {}
    
    on() {
        this.spinner.show()
    }
    
    off() {
        this.spinner.hide()
    }
}
```


