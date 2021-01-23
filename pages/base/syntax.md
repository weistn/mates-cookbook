#define:#
Parenthood: text
Parents: #root

<h1{{if .ID}} id="{{.ID}}"{{end}}{{if .Class}} class="{{.Class}}"{{end}}{{if .Style}} style="{{.Style}}"{{end}}>{{.Content}}</h1>

#define:##
Parenthood: text
Parents: #root

<h2{{if .ID}} id="{{.ID}}"{{end}}{{if .Class}} class="{{.Class}}"{{end}}{{if .Style}} style="{{.Style}}"{{end}}>{{.Content}}</h2>

#define:#time
Parenthood: text
Parents: #root

<div {{if .ID}} id="{{.ID}}"{{end}}{{if .Class}} class="time;{{.Class}}"{{else}} class="time"{{end}}{{if .Style}} style="{{.Style}}"{{end}}>{{.Content}}</div>

#define:#servings
Parenthood: text
Parents: #root

<div {{if .ID}} id="{{.ID}}"{{end}}{{if .Class}} class="servings;{{.Class}}"{{else}} class="servings"{{end}}{{if .Style}} style="{{.Style}}"{{end}}>{{.Content}}</div>
