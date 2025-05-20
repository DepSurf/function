# Function: <code>devlink_traps_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81983fd0)
Location: net/core/devlink.c:7879
Inline: False
```
**Symbols:**

```
ffffffff81983fd0-ffffffff81984504: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5ee20)
Location: net/core/devlink.c:8816
Inline: False
```
**Symbols:**

```
ffffffff81a5ee20-ffffffff81a5efec: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a65c80)
Location: net/core/devlink.c:9775
Inline: False
```
**Symbols:**

```
ffffffff81a65c80-ffffffff81a65e4c: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4b440)
Location: net/core/devlink.c:10039
Inline: False
```
**Symbols:**

```
ffffffff81a4b440-ffffffff81a4b7ab: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:10981
Inline: False
```
**Symbols:**

```
ffffffff81d38aca-ffffffff81d38adf: devlink_traps_register.cold (STB_LOCAL)
ffffffff81b03cb0-ffffffff81b040c7: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:11577
Inline: False
```
**Symbols:**

```
ffffffff81f052f9-ffffffff81f0530e: devlink_traps_register.cold (STB_LOCAL)
ffffffff81c85220-ffffffff81c8562a: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e3f800)
Location: net/core/devlink.c:12436
Inline: False
```
**Symbols:**

```
ffffffff81e3f800-ffffffff81e3f883: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203fff0)
Location: net/devlink/leftover.c:9031
Inline: False
```
**Symbols:**

```
ffffffff8203fff0-ffffffff82040070: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82116ab0)
Location: net/devlink/trap.c:1398
Inline: False
```
**Symbols:**

```
ffffffff82116ab0-ffffffff82116b30: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2c620)
Location: net/core/devlink.c:7879
Inline: False
```
**Symbols:**

```
ffff800010c2c620-ffff800010c2cac0: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d431cc)
Location: net/core/devlink.c:7879
Inline: False
```
**Symbols:**

```
c0d431cc-c0d43714: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d23380)
Location: net/core/devlink.c:7879
Inline: False
```
**Symbols:**

```
c000000000d23380-c000000000d24084: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a3b1a)
Location: net/core/devlink.c:7879
Inline: False
```
**Symbols:**

```
ffffffe0007a3b1a-ffffffe0007a3f4c: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81923e40)
Location: net/core/devlink.c:7879
Inline: False
```
**Symbols:**

```
ffffffff81923e40-ffffffff81924374: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818ddbf0)
Location: net/core/devlink.c:7879
Inline: False
```
**Symbols:**

```
ffffffff818ddbf0-ffffffff818de124: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81974fd0)
Location: net/core/devlink.c:7879
Inline: False
```
**Symbols:**

```
ffffffff81974fd0-ffffffff81975504: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_traps_register(struct devlink *devlink, const struct devlink_trap *traps, size_t traps_count, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819974c0)
Location: net/core/devlink.c:7879
Inline: False
```
**Symbols:**

```
ffffffff819974c0-ffffffff819979f4: devlink_traps_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
