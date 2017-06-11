# angular-easy-spinner
Module to add global spinner to your Angular projects.

## Installation
Clone repo and place easy-spinner directory in your app directory:

<pre style="max-height: 100px;"><code>src
    │    ├── app
    │    │   ├── easy-spinner
    
Then import SpinnerModule in app.module.ts:
```
@NgModule({
  declarations: [AppComponent],
  imports: [
    // Angular Modules
    BrowserModule,
    CommonModule,
    RouterModule,

    // Custom Modules
    SpinnerModule,
  ],
  providers: [],
  bootstrap: [AppComponent]
})
```

## Usage
