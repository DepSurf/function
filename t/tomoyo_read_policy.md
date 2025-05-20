# Function: <code>tomoyo_read_policy</code>

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
In security/tomoyo/common.c (ffffffff81369e7b)
Location: security/tomoyo/common.c:1798
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff8139fe13)
Location: security/tomoyo/common.c:1798
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff813b69a3)
Location: security/tomoyo/common.c:1798
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff813ccfc3)
Location: security/tomoyo/common.c:1798
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff813f3463)
Location: security/tomoyo/common.c:1799
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff8142429a)
Location: security/tomoyo/common.c:1799
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff81440bfa)
Location: security/tomoyo/common.c:1800
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff8146e7db)
Location: security/tomoyo/common.c:1854
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff814885db)
Location: security/tomoyo/common.c:1856
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tomoyo_read_policy(struct tomoyo_io_buffer *head, const int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814dea70)
Location: security/tomoyo/common.c:1856
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
```
**Symbols:**

```
ffffffff814dea70-ffffffff814dedb0: tomoyo_read_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tomoyo_read_policy(struct tomoyo_io_buffer *head, const int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff814fbe90)
Location: security/tomoyo/common.c:1856
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
```
**Symbols:**

```
ffffffff814fbe90-ffffffff814fc1d0: tomoyo_read_policy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tomoyo_read_policy(struct tomoyo_io_buffer *head, const int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/common.c (ffffffff81502630)
Location: security/tomoyo/common.c:1856
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_read_exception
```
**Symbols:**

```
ffffffff81502630-ffffffff81502974: tomoyo_read_policy (STB_LOCAL)
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
In security/tomoyo/common.c (ffffffff81561047)
Location: security/tomoyo/common.c:1856
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff815fc087)
Location: security/tomoyo/common.c:1847
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff816acdf7)
Location: security/tomoyo/common.c:1847
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff816e5827)
Location: security/tomoyo/common.c:1847
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff817224d7)
Location: security/tomoyo/common.c:1848
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffff80001057b06c)
Location: security/tomoyo/common.c:1856
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (c072e634)
Location: security/tomoyo/common.c:1856
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (c0000000006e5cf4)
Location: security/tomoyo/common.c:1856
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffe0003cce82)
Location: security/tomoyo/common.c:1856
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff81480bbb)
Location: security/tomoyo/common.c:1856
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff814715db)
Location: security/tomoyo/common.c:1856
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff8147cc5b)
Location: security/tomoyo/common.c:1856
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
In security/tomoyo/common.c (ffffffff81494d6b)
Location: security/tomoyo/common.c:1856
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_read_exception
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
</ul>
