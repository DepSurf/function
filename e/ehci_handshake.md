# Function: <code>ehci_handshake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816311e0)
Location: drivers/usb/host/ehci-hcd.c:160
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
```
**Symbols:**

```
ffffffff816311e0-ffffffff81631247: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81697b4f)
Location: drivers/usb/host/ehci-hcd.c:160
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff81691db0-ffffffff81691e17: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c603f)
Location: drivers/usb/host/ehci-hcd.c:160
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff816bfe90-ffffffff816bfef7: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816da81b)
Location: drivers/usb/host/ehci-hcd.c:160
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff816d4840-ffffffff816d48a7: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81746f50)
Location: drivers/usb/host/ehci-hcd.c:147
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff81740f30-ffffffff81740f97: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817853e4)
Location: drivers/usb/host/ehci-hcd.c:147
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff81781ae0-ffffffff81781b47: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817ae954)
Location: drivers/usb/host/ehci-hcd.c:147
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff817a8300-ffffffff817a8367: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817ed784)
Location: drivers/usb/host/ehci-hcd.c:147
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff817e7560-ffffffff817e75c7: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8181e654)
Location: drivers/usb/host/ehci-hcd.c:147
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff81818420-ffffffff81818487: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818ed532)
Location: drivers/usb/host/ehci-hcd.c:148
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff818e9660-ffffffff818e96c7: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f6827)
Location: drivers/usb/host/ehci-hcd.c:148
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff818f2570-ffffffff818f25d7: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818da3bc)
Location: drivers/usb/host/ehci-hcd.c:148
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff818d5c40-ffffffff818d5ca7: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81975e68)
Location: drivers/usb/host/ehci-hcd.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff81970900-ffffffff81970967: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad19e8)
Location: drivers/usb/host/ehci-hcd.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff81acb160-ffffffff81acb1f4: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5c488)
Location: drivers/usb/host/ehci-hcd.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff81c55830-ffffffff81c558c4: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc3b08)
Location: drivers/usb/host/ehci-hcd.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff81cbcdc0-ffffffff81cbce54: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d789f5)
Location: drivers/usb/host/ehci-hcd.c:149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff81d71b30-ffffffff81d71bc4: ehci_handshake (STB_GLOBAL)
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
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a54d68)
Location: drivers/usb/host/ehci-hcd.c:147
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffff800010a54d68-ffff800010a54e0c: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b2ce8c)
Location: drivers/usb/host/ehci-hcd.c:147
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
c0b236e8-c0b2376c: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b1e6e0)
Location: drivers/usb/host/ehci-hcd.c:147
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
c000000000b1e6e0-c000000000b1e7f8: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe000678276)
Location: drivers/usb/host/ehci-hcd.c:147
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffe00066de82-ffffffe00066def2: ehci_handshake (STB_GLOBAL)
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
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d6a34)
Location: drivers/usb/host/ehci-hcd.c:147
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff817d0800-ffffffff817d0867: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818134d4)
Location: drivers/usb/host/ehci-hcd.c:147
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff8180d2a0-ffffffff8180d307: ehci_handshake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ehci_handshake(struct ehci_hcd *ehci, void *ptr, u32 mask, u32 done, int usec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8182dfa4)
Location: drivers/usb/host/ehci-hcd.c:147
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_hub_control
  - drivers/usb/host/ehci-hcd.c:ehci_reset
  - drivers/usb/host/ehci-hcd.c:ehci_halt
```
**Symbols:**

```
ffffffff818273b0-ffffffff81827417: ehci_handshake (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
