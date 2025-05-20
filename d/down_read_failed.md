# Function: <code>down_read_failed</code>

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
In drivers/tty/tty_ldsem.c (ffffffff81823b81)
Location: drivers/tty/tty_ldsem.c:200
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (ffffffff8189e801)
Location: drivers/tty/tty_ldsem.c:200
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (ffffffff818d36a1)
Location: drivers/tty/tty_ldsem.c:200
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (ffffffff8190a7dc)
Location: drivers/tty/tty_ldsem.c:202
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (ffffffff81994b3c)
Location: drivers/tty/tty_ldsem.c:200
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (ffffffff819f10cd)
Location: drivers/tty/tty_ldsem.c:200
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (ffffffff81a2c44d)
Location: drivers/tty/tty_ldsem.c:157
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (ffffffff81a9c5ed)
Location: drivers/tty/tty_ldsem.c:156
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (ffffffff81ad3e3d)
Location: drivers/tty/tty_ldsem.c:156
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ld_semaphore *down_read_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81bcbdf0)
Location: drivers/tty/tty_ldsem.c:156
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff81bcbdf0-ffffffff81bcc06f: down_read_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ld_semaphore *down_read_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81c44c10)
Location: drivers/tty/tty_ldsem.c:156
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff81c44c10-ffffffff81c44e8f: down_read_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ld_semaphore *down_read_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81c37e80)
Location: drivers/tty/tty_ldsem.c:156
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff81c37e80-ffffffff81c380f4: down_read_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ld_semaphore *down_read_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81d56760)
Location: drivers/tty/tty_ldsem.c:156
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff81d56760-ffffffff81d569b6: down_read_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ld_semaphore *down_read_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81f288f0)
Location: drivers/tty/tty_ldsem.c:156
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff81f288f0-ffffffff81f28b4f: down_read_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ld_semaphore *down_read_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff820d4550)
Location: drivers/tty/tty_ldsem.c:156
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff820d4550-ffffffff820d47af: down_read_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ld_semaphore *down_read_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff82158760)
Location: drivers/tty/tty_ldsem.c:156
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff82158760-ffffffff821589bf: down_read_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ld_semaphore *down_read_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8223bfe0)
Location: drivers/tty/tty_ldsem.c:156
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
**Symbols:**

```
ffffffff8223bfe0-ffffffff8223c23f: down_read_failed (STB_LOCAL)
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
In drivers/tty/tty_ldsem.c (ffff800010da6a5c)
Location: drivers/tty/tty_ldsem.c:156
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (c0e9e864)
Location: drivers/tty/tty_ldsem.c:156
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (c000000000ee92e4)
Location: drivers/tty/tty_ldsem.c:156
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (ffffffe0008c8d68)
Location: drivers/tty/tty_ldsem.c:156
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (ffffffff81a72cad)
Location: drivers/tty/tty_ldsem.c:156
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (ffffffff81a2f07d)
Location: drivers/tty/tty_ldsem.c:156
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (ffffffff81adf0bd)
Location: drivers/tty/tty_ldsem.c:156
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
In drivers/tty/tty_ldsem.c (ffffffff81aeb84b)
Location: drivers/tty/tty_ldsem.c:156
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
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
