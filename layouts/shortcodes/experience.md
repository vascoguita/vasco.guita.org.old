<style>
    .row {
        display: flex; /* equal height of the children */
    }

    .col {
        flex: 1; /* equal height of the children */
    }

    .col p {
        margin-inline-start: initial;
        padding-inline-start: initial;
        border-inline-start: initial;
        line-height: initial;
        margin: initial;
    }
</style>

<div class="row">
    <div class="col">
        <img src="{{ .Get `logo` }}">
    </div>
    <div class="col">
            <p>{{ .Get "title" }}</p>
            <p class="column-item">{{ .Get "company" }}</p>
            <p class="column-item">{{ .Get "start" }} - {{ if (.Get "end") }}{{ .Get "end" }}{{ else }}present{{ end }}</p>
            <p class="column-item">{{ .Get "location" }}</p>
    </div>
</div>