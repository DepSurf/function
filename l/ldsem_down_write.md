# Function: <code>ldsem_down_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81823d30)
Location: drivers/tty/tty_ldsem.c:390
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
```
**Symbols:**

```
ffffffff81823d30-ffffffff81823f19: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8189e9e0)
Location: drivers/tty/tty_ldsem.c:390
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff8189e9e0-ffffffff8189ebc7: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff818d3890)
Location: drivers/tty/tty_ldsem.c:390
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff818d3890-ffffffff818d3a7a: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8190a990)
Location: drivers/tty/tty_ldsem.c:390
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff8190a990-ffffffff8190ab83: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81994cf0)
Location: drivers/tty/tty_ldsem.c:388
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff81994cf0-ffffffff81994ef1: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff819f12a0)
Location: drivers/tty/tty_ldsem.c:388
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff819f12a0-ffffffff819f14a0: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81a2c620)
Location: drivers/tty/tty_ldsem.c:364
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff81a2c620-ffffffff81a2c85f: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81a9c7a0)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff81a9c7a0-ffffffff81a9c9c4: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81ad3ff0)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff81ad3ff0-ffffffff81ad4214: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81bcc2b0)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff81bcc2b0-ffffffff81bcc302: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81c450d0)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff81c450d0-ffffffff81c45122: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81c38350)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff81c38350-ffffffff81c383a2: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81d56be0)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff81d56be0-ffffffff81d56c32: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81f28dc0)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff81f28dc0-ffffffff81f28e19: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff820d4a50)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff820d4a50-ffffffff820d4aa9: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff82158c60)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff82158c60-ffffffff82158cb9: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff8223c4e0)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff8223c4e0-ffffffff8223c539: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffff800010da6cd0)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffff800010da6cd0-ffff800010da7004: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (c0e9eaac)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
c0e9eaac-c0e9ed74: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (c000000000ee9610)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
c000000000ee9610-c000000000ee9a04: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffe0008c8f88)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffe0008c8f88-ffffffe0008c91e6: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81a72e60)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff81a72e60-ffffffff81a73084: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81a2f220)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff81a2f220-ffffffff81a2f432: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81adf270)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff81adf270-ffffffff81adf494: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ldsem_down_write(struct ld_semaphore *sem, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldsem.c (ffffffff81aeb9e0)
Location: drivers/tty/tty_ldsem.c:363
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_release
  - drivers/tty/tty_ldisc.c:tty_ldisc_lock
```
**Symbols:**

```
ffffffff81aeb9e0-ffffffff81aebbf4: ldsem_down_write (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
