double ma 0 = iMA(NULL, 0,12,0,0,0,0)

MqlTick A[];
ArraySetAsSeries(A, true);
CopyTicks(NULL, A);
prinf


CopyRates


MqlRates rates[];
ArraySetAsSeries[rates,true];
CopyRates(NULL, 0, 0, 10, rates.Digits());
printf(rates[0].open);
