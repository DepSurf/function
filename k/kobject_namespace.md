# Function: <code>kobject_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813eba70)
Location: lib/kobject.c:30
Inline: False
Direct callers:
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_add_internal
  - drivers/base/core.c:device_rename
```
**Symbols:**

```
ffffffff813eba70-ffffffff813ebab8: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81431e40)
Location: lib/kobject.c:30
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - drivers/base/core.c:device_rename
```
**Symbols:**

```
ffffffff81431e40-ffffffff81431e88: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144e0b0)
Location: lib/kobject.c:30
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - drivers/base/core.c:device_rename
```
**Symbols:**

```
ffffffff8144e0b0-ffffffff8144e0f8: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818ee350)
Location: lib/kobject.c:30
Inline: False
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff818ee350-ffffffff818ee392: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81974610)
Location: lib/kobject.c:30
Inline: False
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81974610-ffffffff8197465b: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d0bd0)
Location: lib/kobject.c:28
Inline: True
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff819d0bd0-ffffffff819d0c21: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0a130)
Location: lib/kobject.c:28
Inline: True
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81a0a130-ffffffff81a0a181: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a79a70)
Location: lib/kobject.c:28
Inline: True
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81a79a70-ffffffff81a79abf: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab0dd0)
Location: lib/kobject.c:28
Inline: True
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81ab0dd0-ffffffff81ab0e1f: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eaf60)
Location: lib/kobject.c:28
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:create_dir
  - drivers/base/core.c:device_rename
```
**Symbols:**

```
ffffffff815eaf60-ffffffff815eafb3: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f880)
Location: lib/kobject.c:28
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:create_dir
  - drivers/base/core.c:device_rename
```
**Symbols:**

```
ffffffff8160f880-ffffffff8160f8d3: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f2fc0)
Location: lib/kobject.c:28
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:create_dir
  - drivers/base/core.c:device_rename
```
**Symbols:**

```
ffffffff815f2fc0-ffffffff815f3013: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81660190)
Location: lib/kobject.c:28
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:create_dir
  - drivers/base/core.c:device_rename
```
**Symbols:**

```
ffffffff81660190-ffffffff816601e3: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81779ce0)
Location: lib/kobject.c:28
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
  - drivers/base/core.c:device_rename
```
**Symbols:**

```
ffffffff81779ce0-ffffffff81779d3d: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const void *kobject_namespace(const struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82022d10)
Location: lib/kobject.c:28
Inline: False
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff82022d10-ffffffff82022d6d: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const void *kobject_namespace(const struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a2d80)
Location: lib/kobject.c:30
Inline: False
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff820a2d80-ffffffff820a2ddd: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const void *kobject_namespace(const struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217ae00)
Location: lib/kobject.c:30
Inline: False
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff8217ae00-ffffffff8217ae5d: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8ad80)
Location: lib/kobject.c:28
Inline: True
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffff800010d8ad80-ffff800010d8ade4: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e854b8)
Location: lib/kobject.c:28
Inline: True
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
c0e854b8-c0e85520: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecc370)
Location: lib/kobject.c:28
Inline: True
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
c000000000ecc370-c000000000ecc418: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b42c8)
Location: lib/kobject.c:28
Inline: True
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffe0008b42c8-ffffffe0008b4306: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a4fc20)
Location: lib/kobject.c:28
Inline: True
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81a4fc20-ffffffff81a4fc6f: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0cd20)
Location: lib/kobject.c:28
Inline: True
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81a0cd20-ffffffff81a0cd6f: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abc010)
Location: lib/kobject.c:28
Inline: True
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81abc010-ffffffff81abc05f: kobject_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const void *kobject_namespace(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac8490)
Location: lib/kobject.c:28
Inline: True
Direct callers:
  - drivers/base/core.c:device_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_add_internal
```
**Symbols:**

```
ffffffff81ac8490-ffffffff81ac84df: kobject_namespace (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kobject *kobj</code> ➡️ <code>const struct kobject *kobj</code>
</li>
</ul>
</details>
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
