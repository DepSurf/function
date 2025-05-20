# Function: <code>next_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108d4a5)
Location: kernel/signal.c:171
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff8108d960-ffffffff8108d98f: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090375)
Location: kernel/signal.c:171
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff810909e0-ffffffff81090a0f: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810952f5)
Location: kernel/signal.c:171
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff81095960-ffffffff8109598f: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092568)
Location: kernel/signal.c:177
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff81092960-ffffffff8109298f: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810993f8)
Location: kernel/signal.c:179
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff81099860-ffffffff8109988e: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d505)
Location: kernel/signal.c:181
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff8109d830-ffffffff8109d85e: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a57d5)
Location: kernel/signal.c:198
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff810a5af0-ffffffff810a5b1e: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa4b5)
Location: kernel/signal.c:208
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff810aa7b0-ffffffff810aa7e8: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0ab5)
Location: kernel/signal.c:208
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff810b0db0-ffffffff810b0de8: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8ef2)
Location: kernel/signal.c:208
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff810b9a20-ffffffff810b9a58: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b41a2)
Location: kernel/signal.c:208
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff810b4cd0-ffffffff810b4d08: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5db2)
Location: kernel/signal.c:206
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff810b68e0-ffffffff810b6918: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c8c32)
Location: kernel/signal.c:207
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff810c9770-ffffffff810c97a8: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e01bb)
Location: kernel/signal.c:207
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff810e1160-ffffffff810e11a8: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110084b)
Location: kernel/signal.c:207
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff81101380-ffffffff811013c8: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110c94b)
Location: kernel/signal.c:208
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff8110d4e0-ffffffff8110d528: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111632b)
Location: kernel/signal.c:199
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff81116e20-ffffffff81116e68: next_signal (STB_GLOBAL)
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
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010b7c4)
Location: kernel/signal.c:208
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffff80001010c7e0-ffff80001010c838: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0364940)
Location: kernel/signal.c:208
Inline: True
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
c0364940-c03649a0: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001533cc)
Location: kernel/signal.c:208
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
c000000000153730-c000000000153778: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cdcfc)
Location: kernel/signal.c:208
Inline: False
Direct callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffe0000cdcfc-ffffffe0000cdd92: next_signal (STB_GLOBAL)
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
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aae25)
Location: kernel/signal.c:208
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff810ab120-ffffffff810ab158: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810997c5)
Location: kernel/signal.c:208
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff81099ac0-ffffffff81099af8: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa385)
Location: kernel/signal.c:208
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff810aa680-ffffffff810aa6b8: next_signal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int next_signal(struct sigpending *pending, sigset_t *mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2465)
Location: kernel/signal.c:208
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
Direct callers:
  - fs/signalfd.c:signalfd_poll
  - fs/signalfd.c:signalfd_poll
```
**Symbols:**

```
ffffffff810b2760-ffffffff810b2798: next_signal (STB_GLOBAL)
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
