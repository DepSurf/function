# Function: <code>kill_dev_dax</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff8173fc90)
Location: drivers/dax/bus.c:355
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff8173fc90-ffffffff8173fcca: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81763e70)
Location: drivers/dax/bus.c:355
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81763e70-ffffffff81763eaa: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff8182463d)
Location: drivers/dax/bus.c:363
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81823cc0-ffffffff81823cfa: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81834ca2)
Location: drivers/dax/bus.c:360
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff818328e0-ffffffff8183291a: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81817e6e)
Location: drivers/dax/bus.c:361
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81815b10-ffffffff81815b4a: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818a2498)
Location: drivers/dax/bus.c:359
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff818a0150-ffffffff818a018a: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff819ebc51)
Location: drivers/dax/bus.c:381
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff819e96e0-ffffffff819e9744: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81b68821)
Location: drivers/dax/bus.c:381
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81b66000-ffffffff81b66064: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81bbbc7d)
Location: drivers/dax/bus.c:395
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81bb9610-ffffffff81bb9674: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81c10406)
Location: drivers/dax/bus.c:396
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81c0dc70-ffffffff81c0dcd4: kill_dev_dax (STB_GLOBAL)
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
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffff800010964140)
Location: drivers/dax/bus.c:355
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffff800010964140-ffff800010964190: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c0a3ab64)
Location: drivers/dax/bus.c:355
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
c0a3ab64-c0a3abc0: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c000000000a1a7c0)
Location: drivers/dax/bus.c:355
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
c000000000a1a7c0-c000000000a1a834: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffe0005d1038)
Location: drivers/dax/bus.c:355
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffe0005d1038-ffffffe0005d1086: kill_dev_dax (STB_GLOBAL)
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
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81718560)
Location: drivers/dax/bus.c:355
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81718560-ffffffff8171859a: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff816f0a90)
Location: drivers/dax/bus.c:355
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/dax/device.c:dev_dax_probe
```
**Symbols:**

```
ffffffff816f0a90-ffffffff816f0aca: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81757330)
Location: drivers/dax/bus.c:355
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81757330-ffffffff8175736a: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kill_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff817727d0)
Location: drivers/dax/bus.c:355
Inline: False
Direct callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff817727d0-ffffffff8177280a: kill_dev_dax (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
