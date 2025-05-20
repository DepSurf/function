# Function: <code>__ipv6_fixup_options</code>

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
struct ipv6_txoptions *__ipv6_fixup_options(struct ipv6_txoptions *opt_space, struct ipv6_txoptions *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81dce240)
Location: net/ipv6/exthdrs.c:1349
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81dce240-ffffffff81dce2da: __ipv6_fixup_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ipv6_txoptions *__ipv6_fixup_options(struct ipv6_txoptions *opt_space, struct ipv6_txoptions *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81f9fe20)
Location: net/ipv6/exthdrs.c:1349
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff81f9fe20-ffffffff81f9feba: __ipv6_fixup_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ipv6_txoptions *__ipv6_fixup_options(struct ipv6_txoptions *opt_space, struct ipv6_txoptions *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff82000900)
Location: net/ipv6/exthdrs.c:1316
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff82000900-ffffffff8200099a: __ipv6_fixup_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ipv6_txoptions *__ipv6_fixup_options(struct ipv6_txoptions *opt_space, struct ipv6_txoptions *opt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff820cf740)
Location: net/ipv6/exthdrs.c:1321
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
**Symbols:**

```
ffffffff820cf740-ffffffff820cf7da: __ipv6_fixup_options (STB_GLOBAL)
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
