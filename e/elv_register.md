# Function: <code>elv_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3470)
Location: block/elevator.c:828
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_init
  - block/deadline-iosched.c:deadline_init
```
**Symbols:**

```
ffffffff813b3470-ffffffff813b3604: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7170)
Location: block/elevator.c:827
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_init
  - block/deadline-iosched.c:deadline_init
```
**Symbols:**

```
ffffffff813f7170-ffffffff813f7304: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81410b80)
Location: block/elevator.c:825
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_init
  - block/deadline-iosched.c:deadline_init
```
**Symbols:**

```
ffffffff81410b80-ffffffff81410d14: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141e590)
Location: block/elevator.c:888
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_init
  - block/deadline-iosched.c:deadline_init
```
**Symbols:**

```
ffffffff8141e590-ffffffff8141e705: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81449280)
Location: block/elevator.c:905
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_init
  - block/deadline-iosched.c:deadline_init
```
**Symbols:**

```
ffffffff81449280-ffffffff814493fc: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:876
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_init
  - block/deadline-iosched.c:deadline_init
  - block/cfq-iosched.c:cfq_init
```
**Symbols:**

```
ffffffff8147d6dd-ffffffff8147d731: elv_register.cold.29 (STB_LOCAL)
ffffffff8147c2e0-ffffffff8147c415: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a3e0)
Location: block/elevator.c:510
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff8149a3e0-ffffffff8149a505: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:511
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff814c903d-ffffffff814c906d: elv_register.cold (STB_LOCAL)
ffffffff814c84d0-ffffffff814c85d5: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e15d0)
Location: block/elevator.c:530
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff814e15d0-ffffffff814e16e4: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815400f0)
Location: block/elevator.c:530
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff815400f0-ffffffff81540204: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155c890)
Location: block/elevator.c:523
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff8155c890-ffffffff8155c9a4: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81565120)
Location: block/elevator.c:523
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff81565120-ffffffff81565234: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c94a0)
Location: block/elevator.c:529
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff815c94a0-ffffffff815c95d6: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674660)
Location: block/elevator.c:536
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff81674660-ffffffff816747b9: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817303a0)
Location: block/elevator.c:500
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff817303a0-ffffffff817304ff: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176c5d0)
Location: block/elevator.c:500
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff8176c5d0-ffffffff8176c751: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817ae800)
Location: block/elevator.c:500
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff817ae800-ffffffff817ae981: elv_register (STB_GLOBAL)
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
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105de580)
Location: block/elevator.c:530
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffff8000105de580-ffff8000105de6d8: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078b4fc)
Location: block/elevator.c:530
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
c078b4fc-c078b664: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c00000000076ffe0)
Location: block/elevator.c:530
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
c00000000076ffe0-c0000000007701ac: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe000421218)
Location: block/elevator.c:530
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffe000421218-ffffffe00042133a: elv_register (STB_GLOBAL)
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
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d9bb0)
Location: block/elevator.c:530
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff814d9bb0-ffffffff814d9cc4: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca560)
Location: block/elevator.c:530
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff814ca560-ffffffff814ca674: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d5c40)
Location: block/elevator.c:530
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff814d5c40-ffffffff814d5d54: elv_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int elv_register(struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ee6f0)
Location: block/elevator.c:530
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_init
```
**Symbols:**

```
ffffffff814ee6f0-ffffffff814ee809: elv_register (STB_GLOBAL)
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
