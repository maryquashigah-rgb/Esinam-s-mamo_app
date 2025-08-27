classdef Esinam7 < matlab.apps.AppBase

    % Properties that correspond to app components
    properties (Access = public)
        UIFigure       matlab.ui.Figure
        EXAMINEButton  matlab.ui.control.Button
        Image          matlab.ui.control.Image
        Image2         matlab.ui.control.Image
        Image3         matlab.ui.control.Image
        Image4         matlab.ui.control.Image
        UITable        matlab.ui.control.Table
        Label          matlab.ui.control.Label
        Label2         matlab.ui.control.Label
        Label3         matlab.ui.control.Label
        Label4         matlab.ui.control.Label
    end

    % Callbacks that handle component events
    methods (Access = private)

        % Button pushed function: EXAMINEButton
        function EXAMINEButtonPushed(app, event)
