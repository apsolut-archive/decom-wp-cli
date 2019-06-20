decom wp cli
===================
![icon of windows](https://raw.githubusercontent.com/apsolut/dotwindows/master/assets/images/icons/icon-decom-windows-02.png)
![icon of awesome](https://raw.githubusercontent.com/apsolut/dotwindows/master/assets/images/icons/icon-decom-awesome.png)


https://developer.wordpress.org/cli/commands/

## List of things

- [Regenerate thumbnails](#regenerate-thumbnails)
- [Empty things](#empty-things)
- [Plugins](#plugins)
- [Themes](#themes)
- [Search & Replace](#search-and-replace)



# Regenerate thumbnails
```wp media regenerate --yes``` - this will regenerate all thumbnails (sizes)

# Empty things:
```wp site empty --yes``` - this will remove all posts, pages, comments

# Plugins
```wp plugin activate PLUGINNAME```

```wp plugin deactivate --all``` - this will deactivate all plugins

# Themes 
```wp theme activate```
```wp theme list```


# Search and Replace 


```wp search-replace 'http://TEST.xyz' 'https://TEST.com' --skip-columns=guid```

# To Explore
```wp --skip-plugins```

```wp --prompt```

```wp --post create --from-post=123```

```wp plugin deactivate --all```