# Function: <code>decode_state</code>

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
In kernel/power/main.c (ffffffff810cd4d6)
Location: kernel/power/main.c:327
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (ffffffff810d1f76)
Location: kernel/power/main.c:328
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (ffffffff810d8b16)
Location: kernel/power/main.c:400
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (ffffffff810d7b16)
Location: kernel/power/main.c:400
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (ffffffff810dfb66)
Location: kernel/power/main.c:455
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (ffffffff810e8205)
Location: kernel/power/main.c:485
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (ffffffff810f3815)
Location: kernel/power/main.c:474
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (ffffffff810fbcc5)
Location: kernel/power/main.c:486
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (ffffffff81108135)
Location: kernel/power/main.c:572
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
suspend_state_t decode_state(const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811129d0)
Location: kernel/power/main.c:611
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff811129d0-ffffffff81112a75: decode_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
suspend_state_t decode_state(const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110faa0)
Location: kernel/power/main.c:611
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff8110faa0-ffffffff8110fb45: decode_state (STB_LOCAL)
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
In kernel/power/main.c (ffffffff8111075a)
Location: kernel/power/main.c:611
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (ffffffff8113014a)
Location: kernel/power/main.c:614
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (ffffffff81151938)
Location: kernel/power/main.c:588
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
suspend_state_t decode_state(const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811801c0)
Location: kernel/power/main.c:592
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff811801c0-ffffffff81180280: decode_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
suspend_state_t decode_state(const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81190f90)
Location: kernel/power/main.c:660
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff81190f90-ffffffff81191050: decode_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
suspend_state_t decode_state(const char *buf, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8119f950)
Location: kernel/power/main.c:644
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
```
**Symbols:**

```
ffffffff8119f950-ffffffff8119fa10: decode_state (STB_LOCAL)
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
In kernel/power/main.c (ffff80001016f3f8)
Location: kernel/power/main.c:572
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (c03b9f38)
Location: kernel/power/main.c:572
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (c0000000001c71b8)
Location: kernel/power/main.c:572
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (0)
Location: kernel/power/main.c:572
Inline: True
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
In kernel/power/main.c (ffffffff81101325)
Location: kernel/power/main.c:572
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (ffffffff810f1635)
Location: kernel/power/main.c:572
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (ffffffff810fe605)
Location: kernel/power/main.c:572
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
In kernel/power/main.c (ffffffff811098c5)
Location: kernel/power/main.c:572
Inline: True
Inline callers:
  - kernel/power/main.c:state_store
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
