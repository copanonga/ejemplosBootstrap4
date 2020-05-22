
# ejemplosBootstrap4

## Índice de contenidos

- [pre-scrollable](#pre-scrollable)
- [Tabs](#tabs)

## pre-scrollable

```
<div class="pre-scrollable" style="max-height: 300px">
  <p>Lorem ipsum...</p>
</div>
```

## Tabs

```
<div class="card">
    <div class="card-body">
        <h4 class="card-title">Título</h4>
        <p class="card-description">Descripción</p>
        <ul class="nav nav-tabs" role="tablist">
            <li class="nav-item">
                <a class="nav-link active" 
                   id="home-tab" 
                   data-toggle="tab" 
                   href="#tab001" 
                   role="tab" 
                   aria-controls="tab001" 
                   aria-selected="true">Tab 001</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" 
                   id="profile-tab" 
                   data-toggle="tab" 
                   href="#tab002" 
                   role="tab" 
                   aria-controls="tab002" 
                   aria-selected="false">Tab 002</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" 
                   id="contact-tab" 
                   data-toggle="tab" 
                   href="#tab003" 
                   role="tab" 
                   aria-controls="tab001" 
                   aria-selected="false">Tab 003</a>
            </li>
        </ul>
        <div class="tab-content">
            <div class="tab-pane fade active show" 
                 id="tab001" 
                 role="tabpanel" 
                 aria-labelledby="tab001-tab">

            </div>
            <div class="tab-pane fade" 
                 id="tab002" 
                 role="tabpanel" 
                 aria-labelledby="tab002-tab">

            </div>
            <div class="tab-pane fade" 
                 id="tab003" 
                 role="tabpanel" 
                 aria-labelledby="tab003-tab">

            </div>
        </div>
    </div>
</div>
```
