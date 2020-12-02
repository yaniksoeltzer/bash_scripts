# bash_scripts
A collection of nice bash scripts, to help out every day.
Best copy scripts to `~/bin`.

The following content describes each script individually


## set_audio
<details><summary>usage</summary>
<p>

change audio output

without arguments, show all visible audio sinks.

```
user@host:~$ set_audio
0  HDA NVidia
1 * B25
2  HD-Audio Generic
```
use sink index input 0,1,2 to change all running audio sink inputs and the default sink.

```
user@host:~$ set_audio 2
```

</p>
</details>

