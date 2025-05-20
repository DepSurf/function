# Function: <code>kobject_cleanup</code>

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
In lib/kobject.c (ffffffff813eb8b0)
Location: lib/kobject.c:615
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
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
In lib/kobject.c (ffffffff81431cb6)
Location: lib/kobject.c:615
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
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
In lib/kobject.c (ffffffff8144df26)
Location: lib/kobject.c:615
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
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
In lib/kobject.c (ffffffff818ee110)
Location: lib/kobject.c:618
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (ffffffff81974402)
Location: lib/kobject.c:618
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
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
In lib/kobject.c (ffffffff819d091c)
Location: lib/kobject.c:633
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
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
In lib/kobject.c (ffffffff81a09f3c)
Location: lib/kobject.c:633
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
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
In lib/kobject.c (ffffffff81a7978c)
Location: lib/kobject.c:664
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
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
In lib/kobject.c (ffffffff81ab0aec)
Location: lib/kobject.c:664
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kobject_cleanup(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815ead30)
Location: lib/kobject.c:682
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff815ead30-ffffffff815eae7e: kobject_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kobject_cleanup(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f650)
Location: lib/kobject.c:679
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff8160f650-ffffffff8160f79e: kobject_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kobject_cleanup(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f2d90)
Location: lib/kobject.c:679
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff815f2d90-ffffffff815f2ede: kobject_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kobject_cleanup(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8165ff70)
Location: lib/kobject.c:679
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff8165ff70-ffffffff816600af: kobject_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kobject_cleanup(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81779a50)
Location: lib/kobject.c:647
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff81779a50-ffffffff81779bb5: kobject_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kobject_cleanup(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82022a40)
Location: lib/kobject.c:655
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff82022a40-ffffffff82022ba5: kobject_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kobject_cleanup(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a2ab0)
Location: lib/kobject.c:656
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff820a2ab0-ffffffff820a2c15: kobject_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kobject_cleanup(struct kobject *kobj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217ab30)
Location: lib/kobject.c:663
Inline: False
Direct callers:
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff8217ab30-ffffffff8217ac95: kobject_cleanup (STB_LOCAL)
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
In lib/kobject.c (ffff800010d8ab90)
Location: lib/kobject.c:664
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (c0e8504c)
Location: lib/kobject.c:664
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In lib/kobject.c (c000000000ecb8b0)
Location: lib/kobject.c:664
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b4118)
Location: lib/kobject.c:664
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
</details>
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
In lib/kobject.c (ffffffff81a4f93c)
Location: lib/kobject.c:664
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
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
In lib/kobject.c (ffffffff81a0ca3c)
Location: lib/kobject.c:664
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
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
In lib/kobject.c (ffffffff81abbd2c)
Location: lib/kobject.c:664
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
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
In lib/kobject.c (ffffffff81ac81bc)
Location: lib/kobject.c:664
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
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
