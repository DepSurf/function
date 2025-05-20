# Function: <code>__ldsem_wake_readers</code>

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
In drivers/tty/tty_ldsem.c (ffffffff814ebc3c)
Location: drivers/tty/tty_ldsem.c:119
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8153cc30)
Location: drivers/tty/tty_ldsem.c:119
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff8153cc30-ffffffff8153ccf3: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81569280)
Location: drivers/tty/tty_ldsem.c:119
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff81569280-ffffffff81569343: __ldsem_wake_readers (STB_LOCAL)
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
In drivers/tty/tty_ldsem.c (ffffffff8157c815)
Location: drivers/tty/tty_ldsem.c:121
Inline: True
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
In drivers/tty/tty_ldsem.c (ffffffff815e1315)
Location: drivers/tty/tty_ldsem.c:119
Inline: True
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
In drivers/tty/tty_ldsem.c (ffffffff8161a5b3)
Location: drivers/tty/tty_ldsem.c:119
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff816377f0)
Location: drivers/tty/tty_ldsem.c:74
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff816377f0-ffffffff816378a1: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8166bad0)
Location: drivers/tty/tty_ldsem.c:74
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff8166bad0-ffffffff8166bb72: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8168e140)
Location: drivers/tty/tty_ldsem.c:74
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff8168e140-ffffffff8168e1e2: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff817403f0)
Location: drivers/tty/tty_ldsem.c:74
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff817403f0-ffffffff817404b7: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8175c320)
Location: drivers/tty/tty_ldsem.c:74
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff8175c320-ffffffff8175c3e7: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff817401c0)
Location: drivers/tty/tty_ldsem.c:74
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff817401c0-ffffffff81740287: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff817c09a0)
Location: drivers/tty/tty_ldsem.c:74
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff817c09a0-ffffffff817c0a67: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff818fd240)
Location: drivers/tty/tty_ldsem.c:74
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff818fd240-ffffffff818fd315: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81a568e0)
Location: drivers/tty/tty_ldsem.c:74
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff81a568e0-ffffffff81a569b5: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81aa0ec0)
Location: drivers/tty/tty_ldsem.c:74
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff81aa0ec0-ffffffff81aa0f95: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81af3920)
Location: drivers/tty/tty_ldsem.c:74
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff81af3920-ffffffff81af39f5: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffff80001085f398)
Location: drivers/tty/tty_ldsem.c:74
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffff80001085f398-ffff80001085f49c: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (c0966848)
Location: drivers/tty/tty_ldsem.c:74
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
c0966848-c096694c: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (c0000000008fe900)
Location: drivers/tty/tty_ldsem.c:74
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
c0000000008fe900-c0000000008fea6c: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffe000537876)
Location: drivers/tty/tty_ldsem.c:74
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffe000537876-ffffffe00053793a: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81653bc0)
Location: drivers/tty/tty_ldsem.c:74
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff81653bc0-ffffffff81653c62: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81633fa0)
Location: drivers/tty/tty_ldsem.c:74
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff81633fa0-ffffffff81634042: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81681f80)
Location: drivers/tty/tty_ldsem.c:74
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff81681f80-ffffffff81682022: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8169c5c0)
Location: drivers/tty/tty_ldsem.c:74
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff8169c5c0-ffffffff8169c662: __ldsem_wake_readers (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
