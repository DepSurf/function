# Function: <code>sel_netnode_sid_slow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff8134d17f)
Location: security/selinux/netnode.c:200
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff81383153)
Location: security/selinux/netnode.c:200
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff81399bd3)
Location: security/selinux/netnode.c:200
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff813b0057)
Location: security/selinux/netnode.c:200
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff813d60f7)
Location: security/selinux/netnode.c:200
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff81406703)
Location: security/selinux/netnode.c:200
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff81422263)
Location: security/selinux/netnode.c:200
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff8144fe70)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff81469cc0)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff814bded0)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff814db90a)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sel_netnode_sid_slow(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netnode.c (0)
Location: security/selinux/netnode.c:189
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff814e2230-ffffffff814e2427: sel_netnode_sid_slow (STB_LOCAL)
ffffffff81be2780-ffffffff81be27ac: sel_netnode_sid_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff8153b2fa)
Location: security/selinux/netnode.c:189
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff815d2ac1)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff81680a61)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff816b8b1e)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff816f556e)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffff800010558428)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (c070d154)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (c0000000006b6458)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffe0003afaf0)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff814622a0)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff81452cd0)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff8145e340)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff81475af2)
Location: security/selinux/netnode.c:190
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
