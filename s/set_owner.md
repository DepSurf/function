# Function: <code>set_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816353c0)
Location: drivers/usb/host/ehci-hub.c:528
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
  - drivers/usb/host/ehci-hcd.c:store_companion
```
**Symbols:**

```
ffffffff816353c0-ffffffff81635466: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81696100)
Location: drivers/usb/host/ehci-hub.c:532
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:store_companion
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff81696100-ffffffff816961ad: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c4350)
Location: drivers/usb/host/ehci-hub.c:540
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:store_companion
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff816c4350-ffffffff816c43fd: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816d9310)
Location: drivers/usb/host/ehci-hub.c:540
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:store_companion
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff816d9310-ffffffff816d93c7: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81745a40)
Location: drivers/usb/host/ehci-hub.c:527
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:store_companion
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff81745a40-ffffffff81745af7: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81786980)
Location: drivers/usb/host/ehci-hub.c:527
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff81786980-ffffffff81786a37: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817af150)
Location: drivers/usb/host/ehci-hub.c:535
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff817af150-ffffffff817af207: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817edf10)
Location: drivers/usb/host/ehci-hub.c:535
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff817edf10-ffffffff817edfbc: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8181edf0)
Location: drivers/usb/host/ehci-hub.c:535
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff8181edf0-ffffffff8181ee9c: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818ede90)
Location: drivers/usb/host/ehci-hub.c:534
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff818ede90-ffffffff818edf3c: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f6db0)
Location: drivers/usb/host/ehci-hub.c:537
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff818f6db0-ffffffff818f6e5c: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818da980)
Location: drivers/usb/host/ehci-hub.c:537
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff818da980-ffffffff818daa2c: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81975f70)
Location: drivers/usb/host/ehci-hub.c:537
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff81975f70-ffffffff81976047: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81acb480)
Location: drivers/usb/host/ehci-hub.c:537
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff81acb480-ffffffff81acb550: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c55b80)
Location: drivers/usb/host/ehci-hub.c:537
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff81c55b80-ffffffff81c55c50: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cbd100)
Location: drivers/usb/host/ehci-hub.c:537
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff81cbd100-ffffffff81cbd1d0: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d71e70)
Location: drivers/usb/host/ehci-hub.c:537
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff81d71e70-ffffffff81d71f40: set_owner (STB_LOCAL)
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
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a55110)
Location: drivers/usb/host/ehci-hub.c:535
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffff800010a55110-ffff800010a5525c: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b2402c)
Location: drivers/usb/host/ehci-hub.c:535
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
c0b2402c-c0b24108: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b1e800)
Location: drivers/usb/host/ehci-hub.c:535
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
c000000000b1e800-c000000000b1e9e4: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe0006725b4)
Location: drivers/usb/host/ehci-hub.c:535
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffe0006725b4-ffffffe000672706: set_owner (STB_LOCAL)
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
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d71d0)
Location: drivers/usb/host/ehci-hub.c:535
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff817d71d0-ffffffff817d727c: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81813c70)
Location: drivers/usb/host/ehci-hub.c:535
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff81813c70-ffffffff81813d1c: set_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_owner(struct ehci_hcd *ehci, int portnum, int new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81827450)
Location: drivers/usb/host/ehci-hub.c:535
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:companion_store
  - drivers/usb/host/ehci-hcd.c:ehci_relinquish_port
```
**Symbols:**

```
ffffffff81827450-ffffffff818274e4: set_owner (STB_LOCAL)
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
