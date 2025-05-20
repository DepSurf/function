# Function: <code>klp_unpatch_func</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff810f87e1)
Location: kernel/livepatch/patch.c:138
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_object
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
In kernel/livepatch/patch.c (ffffffff81102a11)
Location: kernel/livepatch/patch.c:139
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_object
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
In kernel/livepatch/patch.c (ffffffff8110b027)
Location: kernel/livepatch/patch.c:139
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_object
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
In kernel/livepatch/patch.c (ffffffff81116817)
Location: kernel/livepatch/patch.c:139
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_unpatch_object
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
In kernel/livepatch/patch.c (ffffffff81120967)
Location: kernel/livepatch/patch.c:135
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
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
In kernel/livepatch/patch.c (ffffffff8112d057)
Location: kernel/livepatch/patch.c:135
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void klp_unpatch_func(struct klp_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8113b6a0)
Location: kernel/livepatch/patch.c:135
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff8113b6a0-ffffffff8113b7d7: klp_unpatch_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void klp_unpatch_func(struct klp_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81135e40)
Location: kernel/livepatch/patch.c:140
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff81135e40-ffffffff81135f77: klp_unpatch_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void klp_unpatch_func(struct klp_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81136c40)
Location: kernel/livepatch/patch.c:140
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff81136c40-ffffffff81136d77: klp_unpatch_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81cafe90)
Location: kernel/livepatch/patch.c:140
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void klp_unpatch_func(struct klp_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:127
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
**Symbols:**

```
ffffffff81182e90-ffffffff81183015: klp_unpatch_func (STB_LOCAL)
ffffffff81e60a95-ffffffff81e60aa9: klp_unpatch_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void klp_unpatch_func(struct klp_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:127
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
**Symbols:**

```
ffffffff811bdef0-ffffffff811be075: klp_unpatch_func (STB_LOCAL)
ffffffff8205a5cd-ffffffff8205a5e1: klp_unpatch_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff820d8e58)
Location: kernel/livepatch/patch.c:127
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff821b4591)
Location: kernel/livepatch/patch.c:127
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
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
In kernel/livepatch/patch.c (c0000000001f1944)
Location: kernel/livepatch/patch.c:135
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
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
In kernel/livepatch/patch.c (ffffffff81125637)
Location: kernel/livepatch/patch.c:135
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
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
In kernel/livepatch/patch.c (ffffffff81118097)
Location: kernel/livepatch/patch.c:135
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
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
In kernel/livepatch/patch.c (ffffffff81123527)
Location: kernel/livepatch/patch.c:135
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
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
In kernel/livepatch/patch.c (ffffffff8112fb47)
Location: kernel/livepatch/patch.c:135
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
