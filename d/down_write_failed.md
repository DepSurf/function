# Function: <code>down_write_failed</code>

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
In drivers/tty/tty_ldsem.c (ffffffff81823d8a)
Location: drivers/tty/tty_ldsem.c:268
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (ffffffff8189ea3a)
Location: drivers/tty/tty_ldsem.c:268
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (ffffffff818d38ea)
Location: drivers/tty/tty_ldsem.c:268
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (ffffffff8190a9f1)
Location: drivers/tty/tty_ldsem.c:269
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (ffffffff81994d51)
Location: drivers/tty/tty_ldsem.c:267
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (ffffffff819f1316)
Location: drivers/tty/tty_ldsem.c:267
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (ffffffff81a2c69a)
Location: drivers/tty/tty_ldsem.c:231
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (ffffffff81a9c81c)
Location: drivers/tty/tty_ldsem.c:230
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (ffffffff81ad406c)
Location: drivers/tty/tty_ldsem.c:230
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ld_semaphore *down_write_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81bcc070)
Location: drivers/tty/tty_ldsem.c:230
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff81bcc070-ffffffff81bcc247: down_write_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ld_semaphore *down_write_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81c44e90)
Location: drivers/tty/tty_ldsem.c:230
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff81c44e90-ffffffff81c45067: down_write_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ld_semaphore *down_write_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81c38100)
Location: drivers/tty/tty_ldsem.c:230
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff81c38100-ffffffff81c382ef: down_write_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ld_semaphore *down_write_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81d569c0)
Location: drivers/tty/tty_ldsem.c:230
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff81d569c0-ffffffff81d56b7e: down_write_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ld_semaphore *down_write_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81f28b50)
Location: drivers/tty/tty_ldsem.c:230
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff81f28b50-ffffffff81f28d49: down_write_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ld_semaphore *down_write_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff820d47c0)
Location: drivers/tty/tty_ldsem.c:230
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff820d47c0-ffffffff820d49b9: down_write_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ld_semaphore *down_write_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff821589d0)
Location: drivers/tty/tty_ldsem.c:230
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff821589d0-ffffffff82158bc9: down_write_failed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ld_semaphore *down_write_failed(struct ld_semaphore *sem, long int count, long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8223c250)
Location: drivers/tty/tty_ldsem.c:230
Inline: False
Direct callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
```
**Symbols:**

```
ffffffff8223c250-ffffffff8223c449: down_write_failed (STB_LOCAL)
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
In drivers/tty/tty_ldsem.c (ffff800010da6d28)
Location: drivers/tty/tty_ldsem.c:230
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (c0e9eb38)
Location: drivers/tty/tty_ldsem.c:230
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (c000000000ee96c4)
Location: drivers/tty/tty_ldsem.c:230
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (ffffffe0008c8ff6)
Location: drivers/tty/tty_ldsem.c:230
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (ffffffff81a72edc)
Location: drivers/tty/tty_ldsem.c:230
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (ffffffff81a2f29c)
Location: drivers/tty/tty_ldsem.c:230
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (ffffffff81adf2ec)
Location: drivers/tty/tty_ldsem.c:230
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
In drivers/tty/tty_ldsem.c (ffffffff81aeba56)
Location: drivers/tty/tty_ldsem.c:230
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_write
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
