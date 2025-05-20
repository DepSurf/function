# Function: <code>software_node_notify</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816aab20)
Location: drivers/base/swnode.c:619
Inline: False
```
**Symbols:**

```
ffffffff816aab20-ffffffff816aac1b: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e4710)
Location: drivers/base/swnode.c:818
Inline: False
```
**Symbols:**

```
ffffffff816e4710-ffffffff816e47fd: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817089e0)
Location: drivers/base/swnode.c:858
Inline: False
```
**Symbols:**

```
ffffffff817089e0-ffffffff81708acd: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c3a70)
Location: drivers/base/swnode.c:850
Inline: False
```
**Symbols:**

```
ffffffff817c3a70-ffffffff817c3b5d: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d87f0)
Location: drivers/base/swnode.c:853
Inline: False
```
**Symbols:**

```
ffffffff817d87f0-ffffffff817d88dd: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bc7b0)
Location: drivers/base/swnode.c:1120
Inline: False
Direct callers:
  - drivers/base/swnode.c:device_remove_software_node
  - drivers/base/swnode.c:device_add_software_node
```
**Symbols:**

```
ffffffff817bc7b0-ffffffff817bc8c6: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void software_node_notify(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81846a10)
Location: drivers/base/swnode.c:1126
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_add_software_node
```
**Symbols:**

```
ffffffff81846a10-ffffffff81846aba: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void software_node_notify(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198b280)
Location: drivers/base/swnode.c:1120
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_add_software_node
```
**Symbols:**

```
ffffffff8198b280-ffffffff8198b34b: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void software_node_notify(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81afa780)
Location: drivers/base/swnode.c:1120
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_add_software_node
```
**Symbols:**

```
ffffffff81afa780-ffffffff81afa84b: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void software_node_notify(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b48b70)
Location: drivers/base/swnode.c:1059
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_add_software_node
```
**Symbols:**

```
ffffffff81b48b70-ffffffff81b48c3b: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void software_node_notify(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81ba0f60)
Location: drivers/base/swnode.c:1062
Inline: False
Direct callers:
  - drivers/base/core.c:device_add
  - drivers/base/swnode.c:device_create_managed_software_node
  - drivers/base/swnode.c:device_add_software_node
```
**Symbols:**

```
ffffffff81ba0f60-ffffffff81ba102b: software_node_notify (STB_GLOBAL)
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
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f6718)
Location: drivers/base/swnode.c:858
Inline: False
```
**Symbols:**

```
ffff8000108f6718-ffff8000108f684c: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e2760)
Location: drivers/base/swnode.c:858
Inline: False
```
**Symbols:**

```
c09e2760-c09e287c: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c000000000991aa0)
Location: drivers/base/swnode.c:858
Inline: False
```
**Symbols:**

```
c000000000991aa0-c000000000991c68: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe00058760e)
Location: drivers/base/swnode.c:858
Inline: False
```
**Symbols:**

```
ffffffe00058760e-ffffffe00058770c: software_node_notify (STB_GLOBAL)
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
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816ce130)
Location: drivers/base/swnode.c:858
Inline: False
```
**Symbols:**

```
ffffffff816ce130-ffffffff816ce21d: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a9460)
Location: drivers/base/swnode.c:858
Inline: False
```
**Symbols:**

```
ffffffff816a9460-ffffffff816a954d: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fc6a0)
Location: drivers/base/swnode.c:858
Inline: False
```
**Symbols:**

```
ffffffff816fc6a0-ffffffff816fc78d: software_node_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int software_node_notify(struct device *dev, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81716f40)
Location: drivers/base/swnode.c:858
Inline: False
```
**Symbols:**

```
ffffffff81716f40-ffffffff8171702d: software_node_notify (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int action</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
