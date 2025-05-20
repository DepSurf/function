# Function: <code>try_then_request_governor</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8187cd40)
Location: drivers/devfreq/devfreq.c:233
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
```
**Symbols:**

```
ffffffff8187cd40-ffffffff8187ce39: try_then_request_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:233
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818c5bc0-ffffffff818c5ca1: try_then_request_governor (STB_LOCAL)
ffffffff818c79eb-ffffffff818c7a0a: try_then_request_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818f9448)
Location: drivers/devfreq/devfreq.c:234
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818f93e0-ffffffff818f94d5: try_then_request_governor (STB_LOCAL)
ffffffff818fa021-ffffffff818fa040: try_then_request_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cf283)
Location: drivers/devfreq/devfreq.c:287
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff819cf250-ffffffff819cf30d: try_then_request_governor (STB_LOCAL)
ffffffff819d0a50-ffffffff819d0a6f: try_then_request_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cee73)
Location: drivers/devfreq/devfreq.c:294
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff819cee40-ffffffff819ceefd: try_then_request_governor (STB_LOCAL)
ffffffff81c2f354-ffffffff81c2f373: try_then_request_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819b3fd3)
Location: drivers/devfreq/devfreq.c:295
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff819b3fa0-ffffffff819b4056: try_then_request_governor (STB_LOCAL)
ffffffff81c21619-ffffffff81c21638: try_then_request_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81a62bb3)
Location: drivers/devfreq/devfreq.c:295
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81a62b80-ffffffff81a62c36: try_then_request_governor (STB_LOCAL)
ffffffff81d33182-ffffffff81d331a1: try_then_request_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81bd4041)
Location: drivers/devfreq/devfreq.c:292
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81bd4000-ffffffff81bd40bd: try_then_request_governor (STB_LOCAL)
ffffffff81eff61d-ffffffff81eff63c: try_then_request_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81d81488)
Location: drivers/devfreq/devfreq.c:292
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81d80130-ffffffff81d801e2: try_then_request_governor.part.0 (STB_LOCAL)
ffffffff81d80200-ffffffff81d80268: try_then_request_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81def848)
Location: drivers/devfreq/devfreq.c:292
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81dee4c0-ffffffff81dee572: try_then_request_governor.part.0 (STB_LOCAL)
ffffffff81dee590-ffffffff81dee5f8: try_then_request_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81ea5e08)
Location: drivers/devfreq/devfreq.c:292
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:governor_store
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81ea4970-ffffffff81ea4a22: try_then_request_governor.part.0 (STB_LOCAL)
ffffffff81ea4a40-ffffffff81ea4aa8: try_then_request_governor (STB_LOCAL)
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
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffff800010b845c8)
Location: drivers/devfreq/devfreq.c:234
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffff800010b845c8-ffff800010b846f4: try_then_request_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c0c68d0c)
Location: drivers/devfreq/devfreq.c:234
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
c0c68d0c-c0c68e04: try_then_request_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c000000000c64390)
Location: drivers/devfreq/devfreq.c:234
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
c000000000c64390-c000000000c64650: try_then_request_governor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffe00072eed2)
Location: drivers/devfreq/devfreq.c:234
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffe00072eed2-ffffffe00072efe0: try_then_request_governor (STB_LOCAL)
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
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8189a778)
Location: drivers/devfreq/devfreq.c:234
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff8189a710-ffffffff8189a805: try_then_request_governor (STB_LOCAL)
ffffffff8189b351-ffffffff8189b370: try_then_request_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81857c48)
Location: drivers/devfreq/devfreq.c:234
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81857be0-ffffffff81857cd5: try_then_request_governor (STB_LOCAL)
ffffffff81858821-ffffffff81858840: try_then_request_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818e9e68)
Location: drivers/devfreq/devfreq.c:234
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818e9e00-ffffffff818e9ef5: try_then_request_governor (STB_LOCAL)
ffffffff818eaa41-ffffffff818eaa60: try_then_request_governor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq_governor *try_then_request_governor(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8190aee8)
Location: drivers/devfreq/devfreq.c:234
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:governor_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff8190ae80-ffffffff8190af75: try_then_request_governor (STB_LOCAL)
ffffffff8190bac1-ffffffff8190bae0: try_then_request_governor.cold (STB_LOCAL)
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
