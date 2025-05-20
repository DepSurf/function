# Function: <code>find_devfreq_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff816ecb50)
Location: drivers/devfreq/devfreq.c:132
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_governor
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:governor_store
```
**Symbols:**

```
ffffffff816ecb50-ffffffff816ecc02: find_devfreq_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81751a10)
Location: drivers/devfreq/devfreq.c:173
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff81751a10-ffffffff81751aca: find_devfreq_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8177d7e0)
Location: drivers/devfreq/devfreq.c:178
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff8177d7e0-ffffffff8177d89e: find_devfreq_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8179c330)
Location: drivers/devfreq/devfreq.c:176
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff8179c330-ffffffff8179c3d8: find_devfreq_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81812570)
Location: drivers/devfreq/devfreq.c:205
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff81812570-ffffffff81812618: find_devfreq_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8185c470)
Location: drivers/devfreq/devfreq.c:205
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff8185c470-ffffffff8185c512: find_devfreq_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8187b9b0)
Location: drivers/devfreq/devfreq.c:203
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff8187b9b0-ffffffff8187ba52: find_devfreq_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:203
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:try_then_request_governor
```
**Symbols:**

```
ffffffff818c5b20-ffffffff818c5bb1: find_devfreq_governor (STB_LOCAL)
ffffffff818c79cc-ffffffff818c79eb: find_devfreq_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818f9eb1)
Location: drivers/devfreq/devfreq.c:204
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff818f9150-ffffffff818f91e2: find_devfreq_governor (STB_LOCAL)
ffffffff818f9eb1-ffffffff818f9ed0: find_devfreq_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819d08e0)
Location: drivers/devfreq/devfreq.c:257
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff819cefe0-ffffffff819cf05b: find_devfreq_governor (STB_LOCAL)
ffffffff819d08e0-ffffffff819d08ff: find_devfreq_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81c2f1e5)
Location: drivers/devfreq/devfreq.c:264
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff819cebc0-ffffffff819cec3b: find_devfreq_governor (STB_LOCAL)
ffffffff81c2f1e5-ffffffff81c2f204: find_devfreq_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81c214aa)
Location: drivers/devfreq/devfreq.c:265
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff819b3d20-ffffffff819b3d9b: find_devfreq_governor (STB_LOCAL)
ffffffff81c214aa-ffffffff81c214c9: find_devfreq_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81d33013)
Location: drivers/devfreq/devfreq.c:265
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff81a62900-ffffffff81a6297b: find_devfreq_governor (STB_LOCAL)
ffffffff81d33013-ffffffff81d33032: find_devfreq_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81eff4b4)
Location: drivers/devfreq/devfreq.c:262
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff81bd3d30-ffffffff81bd3db3: find_devfreq_governor (STB_LOCAL)
ffffffff81eff4b4-ffffffff81eff4d3: find_devfreq_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81d81495)
Location: drivers/devfreq/devfreq.c:262
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff81d7fcc0-ffffffff81d7fd67: find_devfreq_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81def855)
Location: drivers/devfreq/devfreq.c:262
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff81dee050-ffffffff81dee0f7: find_devfreq_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81ea5e15)
Location: drivers/devfreq/devfreq.c:262
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff81ea4500-ffffffff81ea45a7: find_devfreq_governor (STB_LOCAL)
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
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffff800010b844f8)
Location: drivers/devfreq/devfreq.c:204
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:try_then_request_governor
  - drivers/devfreq/devfreq.c:try_then_request_governor
```
**Symbols:**

```
ffff800010b844f8-ffff800010b845c4: find_devfreq_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c0c6893c)
Location: drivers/devfreq/devfreq.c:204
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
c0c6893c-c0c68a00: find_devfreq_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c000000000c63c60)
Location: drivers/devfreq/devfreq.c:204
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
c000000000c63c60-c000000000c63e34: find_devfreq_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffe00072dda0)
Location: drivers/devfreq/devfreq.c:204
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffe00072dda0-ffffffe00072de56: find_devfreq_governor (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8189b1e1)
Location: drivers/devfreq/devfreq.c:204
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff8189a480-ffffffff8189a512: find_devfreq_governor (STB_LOCAL)
ffffffff8189b1e1-ffffffff8189b200: find_devfreq_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818586b1)
Location: drivers/devfreq/devfreq.c:204
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff81857950-ffffffff818579e2: find_devfreq_governor (STB_LOCAL)
ffffffff818586b1-ffffffff818586d0: find_devfreq_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818ea8d1)
Location: drivers/devfreq/devfreq.c:204
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff818e9b70-ffffffff818e9c02: find_devfreq_governor (STB_LOCAL)
ffffffff818ea8d1-ffffffff818ea8f0: find_devfreq_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *find_devfreq_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8190b951)
Location: drivers/devfreq/devfreq.c:204
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_remove_governor
  - drivers/devfreq/devfreq.c:devfreq_add_governor
```
**Symbols:**

```
ffffffff8190abf0-ffffffff8190ac82: find_devfreq_governor (STB_LOCAL)
ffffffff8190b951-ffffffff8190b970: find_devfreq_governor.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
