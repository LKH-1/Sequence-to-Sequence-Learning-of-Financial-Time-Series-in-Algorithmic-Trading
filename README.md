## bachelor-thesis

More info to come later!

## Compiling the document

Run `python make.py` in the project root directory. If you intend to work continuously on the thesis, run `python make.py watch` to have [pymake](https://github.com/philiparvidsson/pymake) automatically recompile the document when a change has been detected.

## Links

* https://student.portal.chalmers.se/sv/chalmersstudier/kandidat-och-examensarbete/examensarbete/Sidor/Planeringsrapport.aspx
* https://student.portal.chalmers.se/sv/chalmersstudier/kandidat-och-examensarbete/kandidatarbete/genomforande/Sidor/Planeringsrapport.aspx

* Writing a Thesis in LaTeX: https://www.sharelatex.com/blog/2013/08/02/thesis-series-pt1.html
* Trading and ML: https://www.youtube.com/playlist?list=PLAwxTw4SYaPnIRwl6rad_mYwEk4Gmj7Mx

## Lectures

* TensorFlow tutorial: https://www.youtube.com/watch?v=Ejec3ID_h0w&feature=youtu.be
* [Tensorflow and deep learning without a PhD, by Martin Görner](https://www.youtube.com/watch?v=vq2nnJ4g6N0)

## Delimitations:

* We will not be writing the source code for the neural networks. Instead, we will use [scikit-learn](http://scikit-learn.org/) and [TensorFlow](https://www.tensorflow.org/)
* We will only use FOREX data as source for financial data (other sources  do not provide real-time data)
* The problem will be treated as a classificatiom problem rather than a regression problem (maybe)

## Questions

### What is maximum drawdown?

Maximum drawdown is the ratio of the all-time high and all-time low prices of a stock:

`max_drawdown = (high - low)/high`

More info: https://www.youtube.com/watch?v=sgqQWb3tT6U

### What is Sharpe ratio?

The Sharpe ratio, named after William Sharpe, is the return of the portfolio minus the risk-free rate of return, divided by a standard deviation of the returns:

`sharpe_ratio = (returns - risk_free_returns)/(standard_dev_of_returns)`

The risk-free rate of return can be considered to be the returns generated by saving money in a svaings account in a bank (as of 2016, normally 0%).

The Sharpe ratio can be understood intuitively this way: Given a stock, its Sharpe ratio is greater the smaller its standard deviation of returns is. For example, when comparing two stocks with equal returns over a given time period, the one with the smaller standard deviation (lower volatility) will have the lower Sharpe ratio, thus indicating that (again, their returns being equal) the one with the *smaller* standard deviation (lower volatility) is the better stock, because it gives the same rate of returns with a lower risk.

More info: https://www.youtube.com/watch?v=5cqstpRndtI

## Todo:

* Läsa om ANN & RNN, kanske LSTM
* Prova att implementera lite i TF