<pre>
```go
type Attributes struct{}

func (a Attributes) Contact() string {
	instagram := "cables_web"
	return instagram
}

func (a Attributes) Life() ([]string, int) {
	language := []string{"French", "English"}
	age := 16
	return language, age
}

func (a Attributes) Coding() (map[string][]string, []string, []string) {
	language := map[string][]string{
		"intermediate": {"python", "js"},
		"learning":     {"go"},
	}
	specialities := []string{"pentest", "fullstack"}
	environnement := []string{"vscode", "sublime text maybe"}
	return language, specialities, environnement
}

func main() {
	attributes := Attributes{}
	fmt.Println(attributes.Contact())
	fmt.Println(attributes.Life())
	fmt.Println(attributes.Coding())
}
```
</pre>
