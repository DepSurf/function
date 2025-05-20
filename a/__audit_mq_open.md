# Function: <code>__audit_mq_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81128f70)
Location: kernel/auditsc.c:2041
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff81128f70-ffffffff8112903b: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81131130)
Location: kernel/auditsc.c:2045
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff81131130-ffffffff811311fb: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113aeb0)
Location: kernel/auditsc.c:2053
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff8113aeb0-ffffffff8113af7b: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113c4c0)
Location: kernel/auditsc.c:2062
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8113c4c0-ffffffff8113c578: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81149240)
Location: kernel/auditsc.c:2085
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81149240-ffffffff811492f8: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81157be0)
Location: kernel/auditsc.c:2092
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81157be0-ffffffff81157c98: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81164be0)
Location: kernel/auditsc.c:2077
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81164be0-ffffffff81164c98: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811716f0)
Location: kernel/auditsc.c:2193
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff811716f0-ffffffff811717a6: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117d570)
Location: kernel/auditsc.c:2193
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8117d570-ffffffff8117d626: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81190820)
Location: kernel/auditsc.c:2245
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81190820-ffffffff811908d6: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118da40)
Location: kernel/auditsc.c:2262
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8118da40-ffffffff8118daf6: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118e9b0)
Location: kernel/auditsc.c:2259
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8118e9b0-ffffffff8118ea7b: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b77c0)
Location: kernel/auditsc.c:2272
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff811b77c0-ffffffff811b788b: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811ea560)
Location: kernel/auditsc.c:2538
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff811ea560-ffffffff811ea643: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff812307a0)
Location: kernel/auditsc.c:2516
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812307a0-ffffffff81230883: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81247310)
Location: kernel/auditsc.c:2515
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81247310-ffffffff812473f3: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81261180)
Location: kernel/auditsc.c:2510
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81261180-ffffffff81261263: __audit_mq_open (STB_GLOBAL)
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
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f2470)
Location: kernel/auditsc.c:2193
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffff8000101f2470-ffff8000101f2514: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0432984)
Location: kernel/auditsc.c:2193
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
c0432984-c0432a28: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000266c80)
Location: kernel/auditsc.c:2193
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
c000000000266c80-c000000000266d24: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000165b52)
Location: kernel/auditsc.c:2193
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
ffffffe000165b52-ffffffe000165bb8: __audit_mq_open (STB_GLOBAL)
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
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81175b90)
Location: kernel/auditsc.c:2193
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81175b90-ffffffff81175c46: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81168d30)
Location: kernel/auditsc.c:2193
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81168d30-ffffffff81168de6: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81173960)
Location: kernel/auditsc.c:2193
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81173960-ffffffff81173a16: __audit_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __audit_mq_open(int oflag, umode_t mode, struct mq_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81181220)
Location: kernel/auditsc.c:2193
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81181220-ffffffff811812d6: __audit_mq_open (STB_GLOBAL)
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
