# SquashedLog
float squashedlog(float x, float g = 1,float h=1) {     return std::tanh(h*signum(x)*std::log(1+std::abs(g*x))/std::log(2)); }
