## Data Stream Analytics
### Sampling<br>
**Goal**:  Sample m items uniformly from a stream<br>
**Problem**:  We don’t know how long the stream is, and it could be effectively infinite.<br>
**Some approaches**:<br>
- Reservoir Sampling<br>
- Min-Wise Sampling<br>
- “Smart” Sampling<br>

### Sketching<br>
**Problem**:  Suppose we want to count the distinct items in a stream.<br>
In sampling, many/most items aren’t sampled, so we don’t know their value.<br>
**Another approach**: 
Sketching<br>
- Model the input stream as a vector.<br>
- A sketch is the result of multiplying the input stream vector by a matrix (to be defined).<br>

