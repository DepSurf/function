# Function: <code>inet_twsk_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff817636e0)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
```
**Symbols:**

```
ffffffff817636e0-ffffffff817637b7: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff817cfb90)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff817cfb90-ffffffff817cfc75: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff817ff980)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff817ff980-ffffffff817ffa65: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fba0)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff8181fba0-ffffffff8181fc73: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff8189eb30)
Location: net/ipv4/inet_timewait_sock.c:43
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff8189eb30-ffffffff8189ec16: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff818f3580)
Location: net/ipv4/inet_timewait_sock.c:43
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff818f3580-ffffffff818f365a: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819210a0)
Location: net/ipv4/inet_timewait_sock.c:43
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff819210a0-ffffffff8192117a: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (0)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff81983a60-ffffffff81983b44: inet_twsk_kill (STB_LOCAL)
ffffffff81983ce8-ffffffff81983cfb: inet_twsk_kill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba250)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff819ba250-ffffffff819ba32e: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4d10)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff81aa4d10-ffffffff81aa4e0a: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf370)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff81aaf370-ffffffff81aaf46a: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a680)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff81a9a680-ffffffff81a9a77a: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55af0)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff81b55af0-ffffffff81b55bea: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce37a0)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff81ce37a0-ffffffff81ce38f1: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea6030)
Location: net/ipv4/inet_timewait_sock.c:50
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff81ea6030-ffffffff81ea62d5: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81f047e0)
Location: net/ipv4/inet_timewait_sock.c:50
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff81f047e0-ffffffff81f04aba: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8ae0)
Location: net/ipv4/inet_timewait_sock.c:48
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff81fc8ae0-ffffffff81fc8dba: inet_twsk_kill (STB_LOCAL)
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
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bcc8)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffff800010c6bcc8-ffff800010c6be50: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (c0d7ab68)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
c0d7ab68-c0d7ac84: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (c000000000d71270)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
c000000000d71270-c000000000d71420: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d16aa)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffe0007d16aa-ffffffe0007d17f4: inet_twsk_kill (STB_LOCAL)
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
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff8195a0c0)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff8195a0c0-ffffffff8195a19e: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff81913bb0)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff81913bb0-ffffffff81913c8e: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819c4890)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff819c4890-ffffffff819c496e: inet_twsk_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet_twsk_kill(struct inet_timewait_sock *tw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce310)
Location: net/ipv4/inet_timewait_sock.c:44
Inline: False
Direct callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
  - net/ipv4/inet_timewait_sock.c:tw_timer_handler
```
**Symbols:**

```
ffffffff819ce310-ffffffff819ce3ea: inet_twsk_kill (STB_LOCAL)
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
