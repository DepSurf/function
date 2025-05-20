# Function: <code>__audit_mq_getsetattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81129100)
Location: kernel/auditsc.c:2108
Inline: False
Direct callers:
  - ipc/mqueue.c:SYSC_mq_getsetattr
```
**Symbols:**

```
ffffffff81129100-ffffffff81129182: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811312c0)
Location: kernel/auditsc.c:2112
Inline: False
Direct callers:
  - ipc/mqueue.c:SYSC_mq_getsetattr
```
**Symbols:**

```
ffffffff811312c0-ffffffff81131342: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113b040)
Location: kernel/auditsc.c:2120
Inline: False
Direct callers:
  - ipc/mqueue.c:SYSC_mq_getsetattr
```
**Symbols:**

```
ffffffff8113b040-ffffffff8113b0c2: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113c660)
Location: kernel/auditsc.c:2129
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff8113c660-ffffffff8113c6e2: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811493e0)
Location: kernel/auditsc.c:2152
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff811493e0-ffffffff81149462: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81157d50)
Location: kernel/auditsc.c:2159
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff81157d50-ffffffff81157dd2: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81164d50)
Location: kernel/auditsc.c:2144
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff81164d50-ffffffff81164dd2: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81171860)
Location: kernel/auditsc.c:2260
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff81171860-ffffffff811718e2: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117d6e0)
Location: kernel/auditsc.c:2260
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff8117d6e0-ffffffff8117d762: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811909a0)
Location: kernel/auditsc.c:2312
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff811909a0-ffffffff81190a22: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118dbc0)
Location: kernel/auditsc.c:2329
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff8118dbc0-ffffffff8118dc42: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118eb30)
Location: kernel/auditsc.c:2326
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff8118eb30-ffffffff8118ebb2: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b7940)
Location: kernel/auditsc.c:2339
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff811b7940-ffffffff811b79c2: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811ea720)
Location: kernel/auditsc.c:2605
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff811ea720-ffffffff811ea7ae: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff812309a0)
Location: kernel/auditsc.c:2583
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff812309a0-ffffffff81230a2e: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81247510)
Location: kernel/auditsc.c:2582
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff81247510-ffffffff8124759e: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81261380)
Location: kernel/auditsc.c:2577
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff81261380-ffffffff8126140e: __audit_mq_getsetattr (STB_GLOBAL)
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
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f25d8)
Location: kernel/auditsc.c:2260
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffff8000101f25d8-ffff8000101f2638: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0432ae0)
Location: kernel/auditsc.c:2260
Inline: False
Direct callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
```
**Symbols:**

```
c0432ae0-c0432b30: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000266de0)
Location: kernel/auditsc.c:2260
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
c000000000266de0-c000000000266e40: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000165c6a)
Location: kernel/auditsc.c:2260
Inline: False
Direct callers:
  - ipc/mqueue.c:__do_sys_mq_getsetattr
```
**Symbols:**

```
ffffffe000165c6a-ffffffe000165cd6: __audit_mq_getsetattr (STB_GLOBAL)
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
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81175d00)
Location: kernel/auditsc.c:2260
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff81175d00-ffffffff81175d82: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81168ea0)
Location: kernel/auditsc.c:2260
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff81168ea0-ffffffff81168f22: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81173ad0)
Location: kernel/auditsc.c:2260
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff81173ad0-ffffffff81173b52: __audit_mq_getsetattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __audit_mq_getsetattr(mqd_t mqdes, struct mq_attr *mqstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81181390)
Location: kernel/auditsc.c:2260
Inline: False
Direct callers:
  - ipc/mqueue.c:do_mq_getsetattr
```
**Symbols:**

```
ffffffff81181390-ffffffff81181412: __audit_mq_getsetattr (STB_GLOBAL)
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
