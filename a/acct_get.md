# Function: <code>acct_get</code>

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
In kernel/acct.c (ffffffff8110c35f)
Location: kernel/acct.c:141
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (ffffffff81113bbf)
Location: kernel/acct.c:141
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (ffffffff8111b2cf)
Location: kernel/acct.c:141
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (ffffffff8111ceef)
Location: kernel/acct.c:143
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (ffffffff811285f6)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bsd_acct_struct *acct_get(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81169100)
Location: kernel/acct.c:144
Inline: False
Direct callers:
  - kernel/acct.c:acct_process
```
**Symbols:**

```
ffffffff81169100-ffffffff8116918d: acct_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bsd_acct_struct *acct_get(struct pid_namespace *ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81165790)
Location: kernel/acct.c:144
Inline: False
Direct callers:
  - kernel/acct.c:acct_process
```
**Symbols:**

```
ffffffff81165790-ffffffff8116582c: acct_get (STB_LOCAL)
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
In kernel/acct.c (0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:163
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:163
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:163
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:163
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (ffffffe0001481d0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
In kernel/acct.c (0)
Location: kernel/acct.c:144
Inline: True
Inline callers:
  - kernel/acct.c:acct_process
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
