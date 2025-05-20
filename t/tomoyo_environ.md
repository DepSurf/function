# Function: <code>tomoyo_environ</code>

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
In security/tomoyo/domain.c (ffffffff8136e31c)
Location: security/tomoyo/domain.c:588
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff813a45e6)
Location: security/tomoyo/domain.c:588
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff813bb166)
Location: security/tomoyo/domain.c:588
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff813d19ae)
Location: security/tomoyo/domain.c:590
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff813f7ebe)
Location: security/tomoyo/domain.c:591
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff81428eff)
Location: security/tomoyo/domain.c:591
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff814457ab)
Location: security/tomoyo/domain.c:591
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff814733eb)
Location: security/tomoyo/domain.c:611
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff8148d18b)
Location: security/tomoyo/domain.c:615
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_environ(struct tomoyo_execve *ee);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814e4180)
Location: security/tomoyo/domain.c:615
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
**Symbols:**

```
ffffffff814e4180-ffffffff814e43fe: tomoyo_environ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_environ(struct tomoyo_execve *ee);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff815015a0)
Location: security/tomoyo/domain.c:613
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
**Symbols:**

```
ffffffff815015a0-ffffffff8150181e: tomoyo_environ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_environ(struct tomoyo_execve *ee);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81508080)
Location: security/tomoyo/domain.c:613
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
**Symbols:**

```
ffffffff81508080-ffffffff81508322: tomoyo_environ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tomoyo_environ(struct tomoyo_execve *ee);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81565310)
Location: security/tomoyo/domain.c:613
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
**Symbols:**

```
ffffffff81565310-ffffffff815655b2: tomoyo_environ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tomoyo_environ(struct tomoyo_execve *ee);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81600b70)
Location: security/tomoyo/domain.c:613
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
**Symbols:**

```
ffffffff81600b70-ffffffff81600e0c: tomoyo_environ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tomoyo_environ(struct tomoyo_execve *ee);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff816b1ac0)
Location: security/tomoyo/domain.c:613
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
**Symbols:**

```
ffffffff816b1ac0-ffffffff816b1d5c: tomoyo_environ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tomoyo_environ(struct tomoyo_execve *ee);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff816ea4a0)
Location: security/tomoyo/domain.c:613
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
**Symbols:**

```
ffffffff816ea4a0-ffffffff816ea740: tomoyo_environ (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tomoyo_environ(struct tomoyo_execve *ee);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff817271e0)
Location: security/tomoyo/domain.c:613
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
```
**Symbols:**

```
ffffffff817271e0-ffffffff817274af: tomoyo_environ (STB_LOCAL)
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
In security/tomoyo/domain.c (ffff800010580588)
Location: security/tomoyo/domain.c:615
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (c0732ab8)
Location: security/tomoyo/domain.c:615
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (c0000000006ee1c4)
Location: security/tomoyo/domain.c:615
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffe0003d12a2)
Location: security/tomoyo/domain.c:615
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff8148576b)
Location: security/tomoyo/domain.c:615
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff8147618b)
Location: security/tomoyo/domain.c:615
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff8148180b)
Location: security/tomoyo/domain.c:615
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
In security/tomoyo/domain.c (ffffffff8149939b)
Location: security/tomoyo/domain.c:615
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
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
