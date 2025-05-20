# Function: <code>tomoyo_commit_condition</code>

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
In security/tomoyo/condition.c (ffffffff8136c3d7)
Location: security/tomoyo/condition.c:392
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff813a25fb)
Location: security/tomoyo/condition.c:392
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff813b917b)
Location: security/tomoyo/condition.c:392
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff813cfa5b)
Location: security/tomoyo/condition.c:392
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff813f5f0b)
Location: security/tomoyo/condition.c:393
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff81426eeb)
Location: security/tomoyo/condition.c:393
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff81443607)
Location: security/tomoyo/condition.c:393
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff8147122b)
Location: security/tomoyo/condition.c:406
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff8148afcb)
Location: security/tomoyo/condition.c:406
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tomoyo_condition *tomoyo_commit_condition(struct tomoyo_condition *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff814e1a80)
Location: security/tomoyo/condition.c:406
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
**Symbols:**

```
ffffffff814e1a80-ffffffff814e1bc1: tomoyo_commit_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tomoyo_condition *tomoyo_commit_condition(struct tomoyo_condition *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff814fee00)
Location: security/tomoyo/condition.c:406
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
**Symbols:**

```
ffffffff814fee00-ffffffff814fef41: tomoyo_commit_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tomoyo_condition *tomoyo_commit_condition(struct tomoyo_condition *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff81505860)
Location: security/tomoyo/condition.c:406
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
**Symbols:**

```
ffffffff81505860-ffffffff81505995: tomoyo_commit_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tomoyo_condition *tomoyo_commit_condition(struct tomoyo_condition *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff815626a0)
Location: security/tomoyo/condition.c:406
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
**Symbols:**

```
ffffffff815626a0-ffffffff815627d5: tomoyo_commit_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tomoyo_condition *tomoyo_commit_condition(struct tomoyo_condition *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff815fd790)
Location: security/tomoyo/condition.c:406
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
**Symbols:**

```
ffffffff815fd790-ffffffff815fd8b7: tomoyo_commit_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tomoyo_condition *tomoyo_commit_condition(struct tomoyo_condition *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff816ae600)
Location: security/tomoyo/condition.c:406
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
**Symbols:**

```
ffffffff816ae600-ffffffff816ae727: tomoyo_commit_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tomoyo_condition *tomoyo_commit_condition(struct tomoyo_condition *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff816e7030)
Location: security/tomoyo/condition.c:406
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
**Symbols:**

```
ffffffff816e7030-ffffffff816e7157: tomoyo_commit_condition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tomoyo_condition *tomoyo_commit_condition(struct tomoyo_condition *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff81723d40)
Location: security/tomoyo/condition.c:406
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
```
**Symbols:**

```
ffffffff81723d40-ffffffff81723e67: tomoyo_commit_condition (STB_LOCAL)
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
In security/tomoyo/condition.c (ffff80001057e56c)
Location: security/tomoyo/condition.c:406
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (c0730ac8)
Location: security/tomoyo/condition.c:406
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (c0000000006eb224)
Location: security/tomoyo/condition.c:406
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffe0003cf664)
Location: security/tomoyo/condition.c:406
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff814835ab)
Location: security/tomoyo/condition.c:406
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff81473fcb)
Location: security/tomoyo/condition.c:406
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff8147f64b)
Location: security/tomoyo/condition.c:406
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
In security/tomoyo/condition.c (ffffffff8149717b)
Location: security/tomoyo/condition.c:406
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_get_condition
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
