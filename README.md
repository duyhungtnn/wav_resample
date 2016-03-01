WAV resampler using SoX
=======================

###Example###

``` c++
    std::string error;

    auto b = wav_resample::resample( input_file, output_file, error, sampling_rate );

    if( b )
    {
        std::cout << "OK\n";
    }
    else
    {
        std::cout << "ERROR: " << error << "\n";
    }
```
