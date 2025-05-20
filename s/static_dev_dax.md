# Function: <code>static_dev_dax</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool static_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff819ebc7b)
Location: drivers/dax/bus.c:153
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff819e95a0-ffffffff819e95bb: static_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool static_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81b6884b)
Location: drivers/dax/bus.c:153
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81b65e80-ffffffff81b65e9b: static_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool static_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81bbbca7)
Location: drivers/dax/bus.c:172
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81bb9490-ffffffff81bb94ab: static_dev_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool static_dev_dax(struct dev_dax *dev_dax);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81c10430)
Location: drivers/dax/bus.c:172
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81c0daf0-ffffffff81c0db0b: static_dev_dax (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
