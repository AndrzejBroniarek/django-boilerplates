# django-boilerplates
Tool for creating objects on building django instances and during tests. Like data migrations, but without headache of migrations.

## Why?

I don't like storing migrations with respository in git. Models are versioned on themselves, working on different branches with migrations stacking up leads to problems. Django-Boilerplates provide simple method to just declare code building objects that your database require to start a project or on database instance during testing.

Just type:

```python manage.py import_boilerplate_data```

and relax.

