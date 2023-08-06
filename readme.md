# wuwx-step-counter

### 使用方法

```
import * as StepCounter from '../../uni_modules/wuwx-step-counter'

StepCounter.startStepCountingUpdates({
	handler: (numberOfSteps, timestamp, error) => {
		console.log(numberOfSteps)
	}
});
```
