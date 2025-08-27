# Chess Position Categorical Evaluation
A program that finetunes ResNet34 using fastai to predict, based on an image of a digital chessboard, whether White, Black, or no one is winning. The categories are determined by the Stockfish evaluations of a position, where None means that the evaluation is inclusively between -1 and 1. The zipped dataset file will be uploaded soon hopefully.
### Further Possibilities
* A segmentation model that takes a real chessboard and determines the equivalent chess position.
* Adding more data for the finetuning.
