<div class="card-container">
  {{ range .Pages }}
    <div class="card">
      <img src="{{ .Params.image }}" alt="{{ .Title }}">
      <h3>{{ .Title }}</h3>
      <p>{{ .Params.description }}</p>
    </div>
  {{ end }}
</div>