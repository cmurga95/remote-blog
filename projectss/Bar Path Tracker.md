# Summary
Quick little project to detect barbell and trace the bar path to use in acceleration training and analyze performance over time.
### Skills used 
Python (vision frameworks like open cv and roboflow)
## Overall workflow 
```mermaid
flowchart TB
	A["First Frame Detection of Barbell (Roboflow)"]
	B["Following the detected barbell (open-cv python)"]
	C["Drawing the path (open-cv and matplotlib)"]

	A-->B-->C
```

![[Pasted image 20250728153306.png]]