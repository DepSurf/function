# Function: <code>tun_flow_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff815ee010)
Location: drivers/net/tun.c:318
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff815ee010-ffffffff815ee083: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8164d100)
Location: drivers/net/tun.c:333
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8164d100-ffffffff8164d173: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8167ee40)
Location: drivers/net/tun.c:333
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8167ee40-ffffffff8167eeb3: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81694200)
Location: drivers/net/tun.c:335
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81694200-ffffffff81694273: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816fe1f0)
Location: drivers/net/tun.c:415
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff816fe1f0-ffffffff816fe263: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173c320)
Location: drivers/net/tun.c:452
Inline: False
```
**Symbols:**

```
ffffffff8173c320-ffffffff8173c393: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8175fc60)
Location: drivers/net/tun.c:458
Inline: False
```
**Symbols:**

```
ffffffff8175fc60-ffffffff8175fcd3: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8179d370)
Location: drivers/net/tun.c:448
Inline: False
```
**Symbols:**

```
ffffffff8179d370-ffffffff8179d3e3: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c0e10)
Location: drivers/net/tun.c:448
Inline: False
```
**Symbols:**

```
ffffffff817c0e10-ffffffff817c0e83: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:419
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_free_netdev
```
**Symbols:**

```
ffffffff8188b120-ffffffff8188b1d9: tun_flow_flush (STB_LOCAL)
ffffffff81890988-ffffffff818909a9: tun_flow_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:390
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_free_netdev
```
**Symbols:**

```
ffffffff818992c0-ffffffff81899379: tun_flow_flush (STB_LOCAL)
ffffffff81c195fb-ffffffff81c1961c: tun_flow_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:398
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_free_netdev
```
**Symbols:**

```
ffffffff8187b6a0-ffffffff8187b759: tun_flow_flush (STB_LOCAL)
ffffffff81c0b456-ffffffff81c0b477: tun_flow_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:404
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
```
**Symbols:**

```
ffffffff8190cbc0-ffffffff8190cc8e: tun_flow_flush (STB_LOCAL)
ffffffff81d109d7-ffffffff81d109f8: tun_flow_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:409
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
```
**Symbols:**

```
ffffffff81a61170-ffffffff81a61250: tun_flow_flush (STB_LOCAL)
ffffffff81edb7dd-ffffffff81edb7fe: tun_flow_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bec480)
Location: drivers/net/tun.c:409
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
```
**Symbols:**

```
ffffffff81bec480-ffffffff81bec580: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c44b00)
Location: drivers/net/tun.c:409
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
```
**Symbols:**

```
ffffffff81c44b00-ffffffff81c44bff: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfa660)
Location: drivers/net/tun.c:409
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_free_netdev
  - drivers/net/tun.c:tun_net_init
```
**Symbols:**

```
ffffffff81cfa660-ffffffff81cfa75f: tun_flow_flush (STB_LOCAL)
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
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109dbea0)
Location: drivers/net/tun.c:448
Inline: False
```
**Symbols:**

```
ffff8000109dbea0-ffff8000109dbf8c: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac1820)
Location: drivers/net/tun.c:448
Inline: False
```
**Symbols:**

```
c0ac1820-c0ac188c: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000a9ccb0)
Location: drivers/net/tun.c:448
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_free_netdev
```
**Symbols:**

```
c000000000a9ccb0-c000000000a9cd60: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe000625968)
Location: drivers/net/tun.c:448
Inline: False
```
**Symbols:**

```
ffffffe000625968-ffffffe0006259e0: tun_flow_flush (STB_LOCAL)
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
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817858e0)
Location: drivers/net/tun.c:448
Inline: False
```
**Symbols:**

```
ffffffff817858e0-ffffffff81785953: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81765230)
Location: drivers/net/tun.c:448
Inline: False
```
**Symbols:**

```
ffffffff81765230-ffffffff817652a3: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b5c90)
Location: drivers/net/tun.c:448
Inline: False
```
**Symbols:**

```
ffffffff817b5c90-ffffffff817b5d03: tun_flow_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tun_flow_flush(struct tun_struct *tun);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817d0030)
Location: drivers/net/tun.c:448
Inline: False
```
**Symbols:**

```
ffffffff817d0030-ffffffff817d00a3: tun_flow_flush (STB_LOCAL)
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
