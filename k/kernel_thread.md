# Function: <code>kernel_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080510)
Location: kernel/fork.c:1790
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff81080510-ffffffff8108053b: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81082350)
Location: kernel/fork.c:1849
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff81082350-ffffffff8108237b: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81086db0)
Location: kernel/fork.c:2011
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff81086db0-ffffffff81086ddb: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81083b00)
Location: kernel/fork.c:2107
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff81083b00-ffffffff81083b2b: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108a3f0)
Location: kernel/fork.c:2116
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff8108a3f0-ffffffff8108a41b: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108dcc0)
Location: kernel/fork.c:2189
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff8108dcc0-ffffffff8108dceb: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81095f50)
Location: kernel/fork.c:2294
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff81095f50-ffffffff81095f7b: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109a440)
Location: kernel/fork.c:2459
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff8109a440-ffffffff8109a4ae: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0a00)
Location: kernel/fork.c:2444
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff810a0a00-ffffffff810a0a6e: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a7870)
Location: kernel/fork.c:2531
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff810a7870-ffffffff810a78db: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3550)
Location: kernel/fork.c:2522
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff810a3550-ffffffff810a35bb: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a4180)
Location: kernel/fork.c:2554
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff810a4180-ffffffff810a41eb: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b59a0)
Location: kernel/fork.c:2647
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff810b59a0-ffffffff810b5a0b: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cbdd0)
Location: kernel/fork.c:2707
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff810cbdd0-ffffffff810cbe5a: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e9440)
Location: kernel/fork.c:2739
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff810e9440-ffffffff810e94ca: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, const char *name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f5040)
Location: kernel/fork.c:2970
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff810f5040-ffffffff810f50d4: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, const char *name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fe3e0)
Location: kernel/fork.c:2960
Inline: False
Direct callers:
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff810fe3e0-ffffffff810fe474: kernel_thread (STB_GLOBAL)
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
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f5378)
Location: kernel/fork.c:2444
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffff8000100f5378-ffff8000100f5408: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0353818)
Location: kernel/fork.c:2444
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
c0353818-c03538bc: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013b440)
Location: kernel/fork.c:2444
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
c00000000013b440-c00000000013b4e0: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c16f6)
Location: kernel/fork.c:2444
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffe0000c16f6-ffffffe0000c176c: kernel_thread (STB_GLOBAL)
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
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109a320)
Location: kernel/fork.c:2444
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff8109a320-ffffffff8109a38e: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81088d60)
Location: kernel/fork.c:2444
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff81088d60-ffffffff81088dce: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109a2d0)
Location: kernel/fork.c:2444
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff8109a2d0-ffffffff8109a33e: kernel_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pid_t kernel_thread(int (*fn)(void *), void *arg, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1f50)
Location: kernel/fork.c:2444
Inline: False
Direct callers:
  - init/main.c:rest_init
  - init/main.c:rest_init
  - kernel/kthread.c:kthreadd
```
**Symbols:**

```
ffffffff810a1f50-ffffffff810a1fbe: kernel_thread (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *name</code>
</li>
<li>
<b>Param reordered. </b>
<code>fn, arg, flags</code> ➡️ <code>fn, arg, name, flags</code>
</li>
</ul>
</details>
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
