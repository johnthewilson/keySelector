# Keylister

This turns any div into a key selector for an associated song

### Example

```
<script type="text/javascript">
    $(function() {
        $( ".key-selector" ).keylister();
    });
</script>

<!-- data-song of the key-selector must match the ID of the song -->
<div class="key-selector" data-song="fortunate-son"></div>

<pre id="fortunate-son">
    G                    F
    Some folks are born made to wave the flag,
    C7                          G
    ooh, they're red, white and blue.
    G                        F
    And when the band plays "Hail to the chief"
    C7                             G
    they point the cannon right at you.
    
    ...
</pre>
```
