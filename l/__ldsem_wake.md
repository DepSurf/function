# Function: <code>__ldsem_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff814ebc00)
Location: drivers/tty/tty_ldsem.c:179
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff814ebc00-ffffffff814ebce3: __ldsem_wake (STB_LOCAL)
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
In drivers/tty/tty_ldsem.c (ffffffff8189e99e)
Location: drivers/tty/tty_ldsem.c:179
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
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
In drivers/tty/tty_ldsem.c (ffffffff818d3842)
Location: drivers/tty/tty_ldsem.c:179
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8157c7e0)
Location: drivers/tty/tty_ldsem.c:181
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff8157c7e0-ffffffff8157c8ce: __ldsem_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff815e12e0)
Location: drivers/tty/tty_ldsem.c:179
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff815e12e0-ffffffff815e13d1: __ldsem_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8161a570)
Location: drivers/tty/tty_ldsem.c:179
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff8161a570-ffffffff8161a65d: __ldsem_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff816378b0)
Location: drivers/tty/tty_ldsem.c:136
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff816378b0-ffffffff816378e9: __ldsem_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8166bb80)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff8166bb80-ffffffff8166bbb9: __ldsem_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8168e1f0)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff8168e1f0-ffffffff8168e229: __ldsem_wake (STB_LOCAL)
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
In drivers/tty/tty_ldsem.c (ffffffff81bcbf77)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:ldsem_wake
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
In drivers/tty/tty_ldsem.c (ffffffff81c44d97)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:ldsem_wake
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
In drivers/tty/tty_ldsem.c (ffffffff81c37ffc)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:ldsem_wake
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
In drivers/tty/tty_ldsem.c (ffffffff81d568c0)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:ldsem_wake
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
In drivers/tty/tty_ldsem.c (ffffffff81f28a3e)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:ldsem_wake
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
In drivers/tty/tty_ldsem.c (ffffffff820d469e)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:ldsem_wake
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
In drivers/tty/tty_ldsem.c (ffffffff821588ae)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:ldsem_wake
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
In drivers/tty/tty_ldsem.c (ffffffff8223c12e)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/tty/tty_ldsem.c:ldsem_wake
  - drivers/tty/tty_ldsem.c:ldsem_wake
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
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffff80001085f4a0)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffff80001085f4a0-ffff80001085f504: __ldsem_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (c096694c)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
c096694c-c0966998: __ldsem_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (c0000000008fea70)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
c0000000008fea70-c0000000008fead4: __ldsem_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffe00053793a)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffe00053793a-ffffffe00053798e: __ldsem_wake (STB_LOCAL)
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
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81653c70)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff81653c70-ffffffff81653ca9: __ldsem_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81634050)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff81634050-ffffffff81634089: __ldsem_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81682030)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff81682030-ffffffff81682069: __ldsem_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __ldsem_wake(struct ld_semaphore *sem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8169c670)
Location: drivers/tty/tty_ldsem.c:135
Inline: True
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_wake
```
**Symbols:**

```
ffffffff8169c670-ffffffff8169c6a9: __ldsem_wake (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
