# Function: <code>tcp_keepalive_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_keepalive_timer(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff817799d0)
Location: net/ipv4/tcp_timer.c:574
Inline: False
```
**Symbols:**

```
ffffffff817799d0-ffffffff81779bf1: tcp_keepalive_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_keepalive_timer(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff817e6ba0)
Location: net/ipv4/tcp_timer.c:618
Inline: False
```
**Symbols:**

```
ffffffff817e6ba0-ffffffff817e6dc1: tcp_keepalive_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_keepalive_timer(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff818172e0)
Location: net/ipv4/tcp_timer.c:624
Inline: False
```
**Symbols:**

```
ffffffff818172e0-ffffffff81817501: tcp_keepalive_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_keepalive_timer(long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff81837680)
Location: net/ipv4/tcp_timer.c:622
Inline: False
```
**Symbols:**

```
ffffffff81837680-ffffffff818378a0: tcp_keepalive_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffff818b6d60)
Location: net/ipv4/tcp_timer.c:632
Inline: False
```
**Symbols:**

```
ffffffff818b6d60-ffffffff818b6feb: tcp_keepalive_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:624
Inline: False
```
**Symbols:**

```
ffffffff8190c5e0-ffffffff8190c8a2: tcp_keepalive_timer (STB_LOCAL)
ffffffff8190d9cc-ffffffff8190d9dd: tcp_keepalive_timer.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:651
Inline: False
```
**Symbols:**

```
ffffffff8193a930-ffffffff8193abd1: tcp_keepalive_timer (STB_LOCAL)
ffffffff8193bdac-ffffffff8193bdbd: tcp_keepalive_timer.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:643
Inline: False
```
**Symbols:**

```
ffffffff8199ece0-ffffffff8199ef78: tcp_keepalive_timer (STB_LOCAL)
ffffffff819a01cc-ffffffff819a01dd: tcp_keepalive_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:650
Inline: False
```
**Symbols:**

```
ffffffff819d5780-ffffffff819d5a18: tcp_keepalive_timer (STB_LOCAL)
ffffffff819d6d8c-ffffffff819d6d9d: tcp_keepalive_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:662
Inline: False
```
**Symbols:**

```
ffffffff81ac2950-ffffffff81ac2c56: tcp_keepalive_timer (STB_LOCAL)
ffffffff81ac392f-ffffffff81ac3940: tcp_keepalive_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:673
Inline: False
```
**Symbols:**

```
ffffffff81ace380-ffffffff81ace686: tcp_keepalive_timer (STB_LOCAL)
ffffffff81c326f7-ffffffff81c32708: tcp_keepalive_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:673
Inline: False
```
**Symbols:**

```
ffffffff81ab9510-ffffffff81ab9816: tcp_keepalive_timer (STB_LOCAL)
ffffffff81c249cc-ffffffff81c249dd: tcp_keepalive_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:673
Inline: False
```
**Symbols:**

```
ffffffff81b76940-ffffffff81b76c4b: tcp_keepalive_timer (STB_LOCAL)
ffffffff81d3b596-ffffffff81d3b5c1: tcp_keepalive_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:677
Inline: False
```
**Symbols:**

```
ffffffff81d06160-ffffffff81d064d9: tcp_keepalive_timer (STB_LOCAL)
ffffffff81f07e4e-ffffffff81f07e79: tcp_keepalive_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:668
Inline: False
```
**Symbols:**

```
ffffffff81ecb4d0-ffffffff81ecb813: tcp_keepalive_timer (STB_LOCAL)
ffffffff820af8be-ffffffff820af8d8: tcp_keepalive_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:705
Inline: False
```
**Symbols:**

```
ffffffff81f2a020-ffffffff81f2a36b: tcp_keepalive_timer (STB_LOCAL)
ffffffff82130c4b-ffffffff82130c64: tcp_keepalive_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:741
Inline: False
```
**Symbols:**

```
ffffffff81feeb90-ffffffff81feeed6: tcp_keepalive_timer (STB_LOCAL)
ffffffff8221241f-ffffffff82212438: tcp_keepalive_timer.cold (STB_LOCAL)
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
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffff800010c88910)
Location: net/ipv4/tcp_timer.c:650
Inline: False
```
**Symbols:**

```
ffff800010c88910-ffff800010c88bf0: tcp_keepalive_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (c0d9771c)
Location: net/ipv4/tcp_timer.c:650
Inline: False
```
**Symbols:**

```
c0d9771c-c0d9797c: tcp_keepalive_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (c000000000d953f0)
Location: net/ipv4/tcp_timer.c:650
Inline: False
```
**Symbols:**

```
c000000000d953f0-c000000000d957ec: tcp_keepalive_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_timer.c (ffffffe0007e967c)
Location: net/ipv4/tcp_timer.c:650
Inline: False
```
**Symbols:**

```
ffffffe0007e967c-ffffffe0007e9920: tcp_keepalive_timer (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:650
Inline: False
```
**Symbols:**

```
ffffffff819755f0-ffffffff81975888: tcp_keepalive_timer (STB_LOCAL)
ffffffff81976bfc-ffffffff81976c0d: tcp_keepalive_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:650
Inline: False
```
**Symbols:**

```
ffffffff8192f0b0-ffffffff8192f348: tcp_keepalive_timer (STB_LOCAL)
ffffffff819306bc-ffffffff819306cd: tcp_keepalive_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:650
Inline: False
```
**Symbols:**

```
ffffffff819dfdc0-ffffffff819e0058: tcp_keepalive_timer (STB_LOCAL)
ffffffff819e13cc-ffffffff819e13dd: tcp_keepalive_timer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void tcp_keepalive_timer(struct timer_list *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_timer.c (0)
Location: net/ipv4/tcp_timer.c:650
Inline: False
```
**Symbols:**

```
ffffffff819e9a80-ffffffff819e9d16: tcp_keepalive_timer (STB_LOCAL)
ffffffff819eb09c-ffffffff819eb0ad: tcp_keepalive_timer.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct timer_list *t</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int data</code>
</li>
</ul>
</details>
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
