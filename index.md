## Ahmed Aboud

PHP Back-End Developer
loves php , laravel

### Controller

```markdown
        $repositories = Repository::where('owner_id',$id)->with('owner')->get();
        return view('github.profile',compact('repositories'));
```
### Contact

E-mail : Ahmed_Aboud_Ali@yahoo.com
