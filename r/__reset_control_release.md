# Function: <code>__reset_control_release</code>

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
In drivers/reset/core.c (ffffffff815714f2)
Location: drivers/reset/core.c:312
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_put_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __reset_control_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815d5830)
Location: drivers/reset/core.c:412
Inline: False
```
**Symbols:**

```
ffffffff815d5830-ffffffff815d587d: __reset_control_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __reset_control_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8160e5f0)
Location: drivers/reset/core.c:442
Inline: False
```
**Symbols:**

```
ffffffff8160e5f0-ffffffff8160e63d: __reset_control_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __reset_control_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8162b530)
Location: drivers/reset/core.c:442
Inline: False
```
**Symbols:**

```
ffffffff8162b530-ffffffff8162b57d: __reset_control_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __reset_control_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8165ee50)
Location: drivers/reset/core.c:581
Inline: False
```
**Symbols:**

```
ffffffff8165ee50-ffffffff8165ee9b: __reset_control_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __reset_control_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81681520)
Location: drivers/reset/core.c:580
Inline: False
```
**Symbols:**

```
ffffffff81681520-ffffffff8168156b: __reset_control_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732cbe)
Location: drivers/reset/core.c:581
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_array_put
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174ee7e)
Location: drivers/reset/core.c:655
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_array_put
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732d8c)
Location: drivers/reset/core.c:792
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
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
In drivers/reset/core.c (ffffffff817b369c)
Location: drivers/reset/core.c:792
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff818eef0a)
Location: drivers/reset/core.c:793
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a46baa)
Location: drivers/reset/core.c:793
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
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
In drivers/reset/core.c (ffffffff81a90d4a)
Location: drivers/reset/core.c:793
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_bulk_put
  - drivers/reset/core.c:__reset_control_bulk_get
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
In drivers/reset/core.c (ffffffff81ae3868)
Location: drivers/reset/core.c:793
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_put_internal
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084c8f8)
Location: drivers/reset/core.c:580
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_put_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0958c04)
Location: drivers/reset/core.c:580
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_put_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008eaa28)
Location: drivers/reset/core.c:580
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_put_internal
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __reset_control_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052c050)
Location: drivers/reset/core.c:580
Inline: False
Direct callers:
  - drivers/reset/core.c:of_reset_control_array_get
```
**Symbols:**

```
ffffffe00052c050-ffffffe00052c0a6: __reset_control_release (STB_LOCAL)
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
void __reset_control_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81646fa0)
Location: drivers/reset/core.c:580
Inline: False
```
**Symbols:**

```
ffffffff81646fa0-ffffffff81646feb: __reset_control_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __reset_control_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81627400)
Location: drivers/reset/core.c:580
Inline: False
```
**Symbols:**

```
ffffffff81627400-ffffffff8162744b: __reset_control_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __reset_control_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81675360)
Location: drivers/reset/core.c:580
Inline: False
```
**Symbols:**

```
ffffffff81675360-ffffffff816753ab: __reset_control_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __reset_control_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8168f9c0)
Location: drivers/reset/core.c:580
Inline: False
```
**Symbols:**

```
ffffffff8168f9c0-ffffffff8168fa0b: __reset_control_release (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
