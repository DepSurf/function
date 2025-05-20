# Function: <code>klp_init_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810e8f97)
Location: kernel/livepatch/core.c:723
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810ef903)
Location: kernel/livepatch/core.c:788
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f6fd3)
Location: kernel/livepatch/core.c:795
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f815c)
Location: kernel/livepatch/core.c:672
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811023fe)
Location: kernel/livepatch/core.c:686
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8110a78d)
Location: kernel/livepatch/core.c:748
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81115f5d)
Location: kernel/livepatch/core.c:748
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8111fd2e)
Location: kernel/livepatch/core.c:767
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112c47e)
Location: kernel/livepatch/core.c:767
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int klp_init_object(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8113a930)
Location: kernel/livepatch/core.c:820
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff8113a930-ffffffff8113aadc: klp_init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int klp_init_object(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81135420)
Location: kernel/livepatch/core.c:820
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81135420-ffffffff811355cc: klp_init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int klp_init_object(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81136300)
Location: kernel/livepatch/core.c:819
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81136300-ffffffff8113648c: klp_init_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int klp_init_object(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:819
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81158ec0-ffffffff81159083: klp_init_object (STB_LOCAL)
ffffffff81cafa93-ffffffff81cafac4: klp_init_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int klp_init_object(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:819
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81182420-ffffffff8118260d: klp_init_object (STB_LOCAL)
ffffffff81e60724-ffffffff81e60756: klp_init_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int klp_init_object(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:844
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff811bd0f0-ffffffff811bd2e1: klp_init_object (STB_LOCAL)
ffffffff8205a4f9-ffffffff8205a52b: klp_init_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int klp_init_object(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:872
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff811cf900-ffffffff811cfaf1: klp_init_object (STB_LOCAL)
ffffffff820d8cfe-ffffffff820d8d30: klp_init_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int klp_init_object(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:872
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff811e4550-ffffffff811e4741: klp_init_object (STB_LOCAL)
ffffffff821b4437-ffffffff821b4469: klp_init_object.cold (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001f0700)
Location: kernel/livepatch/core.c:767
Inline: True
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81124a5e)
Location: kernel/livepatch/core.c:767
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811174be)
Location: kernel/livepatch/core.c:767
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112294e)
Location: kernel/livepatch/core.c:767
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112ef5e)
Location: kernel/livepatch/core.c:767
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
