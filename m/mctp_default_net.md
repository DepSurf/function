# Function: <code>mctp_default_net</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int mctp_default_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff81e3a660)
Location: net/mctp/route.c:559
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/device.c:mctp_add_dev
```
**Symbols:**

```
ffffffff81e3a660-ffffffff81e3a677: mctp_default_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int mctp_default_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82013bf0)
Location: net/mctp/route.c:567
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/device.c:mctp_add_dev
```
**Symbols:**

```
ffffffff82013bf0-ffffffff82013c07: mctp_default_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int mctp_default_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82090a70)
Location: net/mctp/route.c:567
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/device.c:mctp_add_dev
```
**Symbols:**

```
ffffffff82090a70-ffffffff82090a87: mctp_default_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int mctp_default_net(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82166fb0)
Location: net/mctp/route.c:567
Inline: False
Direct callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
  - net/mctp/device.c:mctp_add_dev
```
**Symbols:**

```
ffffffff82166fb0-ffffffff82166fc7: mctp_default_net (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
