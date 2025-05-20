# Function: <code>tomoyo_write_env</code>

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
In security/tomoyo/environ.c (ffffffff8136e99d)
Location: security/tomoyo/environ.c:93
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff813a4c7e)
Location: security/tomoyo/environ.c:93
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff813bb7fe)
Location: security/tomoyo/environ.c:93
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff813d20f6)
Location: security/tomoyo/environ.c:93
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff813f8606)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff814295fe)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff81445ebe)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff81473ad7)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff8148d877)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_write_env(struct tomoyo_acl_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/environ.c (ffffffff814e4940)
Location: security/tomoyo/environ.c:94
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff814e4940-ffffffff814e4a1a: tomoyo_write_env (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_write_env(struct tomoyo_acl_param *param);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/environ.c (ffffffff81501d40)
Location: security/tomoyo/environ.c:94
Inline: False
Direct callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
```
**Symbols:**

```
ffffffff81501d40-ffffffff81501e1a: tomoyo_write_env (STB_LOCAL)
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
In security/tomoyo/environ.c (ffffffff81508a07)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff81565c87)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff81601526)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff816b24d6)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff816eaec6)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff81727c96)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffff800010580d40)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (c073315c)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (c0000000006ef218)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffe0003d174e)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff81485e57)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff81476877)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff81481ef7)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
In security/tomoyo/environ.c (ffffffff81499a87)
Location: security/tomoyo/environ.c:94
Inline: True
Inline callers:
  - security/tomoyo/environ.c:tomoyo_write_misc
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
</ul>
